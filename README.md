# Copy a deleted EC2 Instance EBS volume to a running instance

## Full Step-by-Step guide with snapshots to both describe and illustrate how I can detach an EBS volume from an EC2 Instance and load that same EBS Volume on another running instance.

### This project demonstrates how to detach an EBS volume from an instance and attach it to another running instance. This project will cover:

* Setting up two EC2 Instances

* Detaching & Deleting the EBS volume from the second instance

* Copy over the EBS Volume & Volume data of first created EC2 Instance to the second created EC2 Instance.

* Create a Snapshot of the EBS Volume from the First Created EC2 Instance 

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



 COPY OVER THE EBS VOLUME & DATA FROM THE FIRST CREATED EC2 INSTANCE TO THE SECOND CREATED EC2 INSTANCE

 * Select the Instance tab from the navigation panel on the left.
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
 * Select the first EC2 Instance that was created.
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
 * Select the Connect Button from the top-right of the Instances Page
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
 * Select the EC2 Instance Connect Tab
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
 * Select the Connect Button at the bottom
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
 * Type "nano proof.txt" into the EC2 Instance Connect
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
 * Type out a text in the nano editor.
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
CREATE A SNAPSHOT OF THE EBS VOLUME FROM THE FIRST CREATED EC2 INSTANCE: 

* Select the Volumes Tab from the navigation panel on the left
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
* Select the EBS Volume for the first created EC2 instance
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
* Select Actions from the top right of the Volumes Page
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
* Select Create Snapshot from the drop-down options.
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
* Select the Snapshots Tab from the navigation panel on the left
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
* Wait until the progress shows one hundred percent
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
* Select Actions from the top right of the Snapshots Page
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
* Select the snapshot that was just created
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
* Select Actions from the top right of the snapshots page
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
* Select Create volume from snapshot from the drop-down options.
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
* Select Create Volume at the bottom of the page.

<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  

* Select the Volumes Tab from the navigation panel on the left

* Wait until the initialization state shows completed.

* Select the recently created volume from the snapshot.

 * Select Actions from the top right of the Volumes Page

 * Select Attach Volume from the drop-down options.

 * Select the EC2 Instance to attach to the volume (in this case the second EC2 Instance)

 * Select the root device option under Device Name.

 * Select the Attach Volume button at the bottom.

 * Select the Instances Tab from the navigation panel on the left

 * Select the second created EC2 Instance
 
 * Select Connect from the top right of the Instances Page

 * Select the EC2 Instance Connect Tab

<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
 
 * Select the Connect Button at the bottom
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  

* Type "nano proof.txt" into the EC2 Instance Connect
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  
 * See previously created text.
<p align="center">  
  <img src="Resources/EBS DELETE VOLUME button.png" alt="Select Delete Volume Button" width="900" />  
</p>  

This proves that the process of copying the EBS Volume from the first EC2 Instance to the Second EC2 Instance was a success.
















##### Contribution Policy

This project is not accepting external contributions, including pull requests or feature requests.

It serves as a personal archive of my learning journey in applying foundational concepts in software development and version control. Active development is not ongoing, and external changes will not be integrated.
