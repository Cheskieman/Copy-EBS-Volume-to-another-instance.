# Copy a deleted EC2 Instance EBS volume to a running instance

## Full Step-by-Step guide with snapshots to both describe and illustrate how I can detach an EBS volume from an EC2 Instance and load that same EBS Volume on another running instance.

### This project demonstrates how to detach an EBS volume from an instance and attach it to another running instance. This project will cover:

* Setting up two EC2 Instances

* Detaching the EBS volume from the second instance

* 

#### Instructions on how to remove an EBS volume from an instance and load it onto another running instance.


CREATE TWO EC2 INSTANCES:

* Select after typing EC2 from AWS Searchbar

<p align="center">  
  <img src="Resources/EC2 SELECT EC2 AWS SEARCH BAR.png" alt="Select EC2 from AWS Searchbar" width="900" />  
</p>  

* Select Instances from the navigation panel on the left

<p align="center">  
  <img src="Resources/EC2 Select Instances from AWS Navigation Panel.png" alt="Select Instances from Navigation Panel" width="900" />  
</p>  
* Select Launch Instance

<p align="center">  
  <img src="Resources/EC2 Select Launch Instance Tab .png" alt="Select Launch Instance " width="900" />  
</p>  
* Give your Instance a name

<p align="center">  
  <img src="Resources/EC2 Give Instance a Name.png" alt="Give Instance a Name" width="900" />  
</p>  
* Select Ubuntu as AMI

<p align="center">  
  <img src="Resources/EC2 SELECT UBUNTU AMI.png" alt="Select Ubuntu as AMI" width="900" />  
</p>  
* Select your Keypair from the dropdown menu after scrolling down to the keypair section.

<p align="center">  
  <img src="Resources/EC2 KEYPAIR .png" alt="Select Keypair " width="900" />  
</p>  
* Select Launch Instance at the bottom.

<p align="center">  
  <img src="Resources/EC2 LAUNCH INSTANCE END.png" alt="Launch Instance" width="900" />  
</p>  

* Repeat all the same steps above, except for giving another name to this second EC2 instance.

  

DETACHING & DELETE THE EBS VOLUME FROM THE SECOND EC2 INSTANCE:

*Select the second EC2 Instance Created

<p align="center">  
  <img src="Resources/EBS Select the 2nd EC2 CREATED.png" alt="Select the 2nd EC2 Instance" width="900" />  
</p>  
* Select Actions from the top right of the Instances Page

<p align="center">  
  <img src="Resources/EBS Select Actions Tab.png" alt="Select Actions" width="900" />  
</p>  
* Select Storage from the drop-down options.

<p align="center">  
  <img src="Resources/EBSV Select Storage from Actions Dropdown.png" alt="Select Storage" width="900" />  
</p>  
* Select Detach Volume.

<p align="center">  
  <img src="Resources/EBS Select Detach Volume from storage.png" alt="Select Detach Volume" width="900" />  
</p>  
* Select the volume you want to detach from the box that appears.

<p align="center">  
  <img src="Resources/EBS Select Volum pop up screen  for detaching.png" alt="Select the Volume to Detach" width="900" />  
</p>  
* Select the Detach Volume Button.

<p align="center">  
  <img src="Resources/EBS Select Detach Volume button.png" alt="Select Detach Volume Button" width="900" />  
</p>  
* Select Volume from the navigation panel on the left.

<p align="center">  
  <img src="Resources/EBS DELETE VOLUME Select Volume from left hand navigation panel.png" alt="Select Volume from Left Handed Navigation Panel" width="900" />  
</p>  

* Select the Volume that was just detached.

<p align="center">  
  <img src="Resources/EBS DELETE VOLUME Select Volume that was attached to the second EC2 Instance.png" alt="Select recently detached Volume" width="900" />  
</p>  

* Select Actions from the top right of the Volumes Page

<p align="center">  
  <img src="Resources/EBS Select Actions Tab.png" alt="Select Actions " width="900" />  
</p>  
* Select Delete Volume

<p align="center">  
  <img src="Resources/EBS DELETE VOLUME Select Delete Volume from actions drop down.png" alt="Select Delete Volume" width="900" />  
</p>  
* Type Delete into the box that appears.

<p align="center">  
  <img src="Resources/EBS DELETE VOLUME type delete volume from box.png" alt="Type Delete" width="900" />  
</p>  
* Select the Delete Button.

<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  


















##### Contribution Policy

This project is not accepting external contributions, including pull requests or feature requests.

It serves as a personal archive of my learning journey in applying foundational concepts in software development and version control. Active development is not ongoing, and external changes will not be integrated.
