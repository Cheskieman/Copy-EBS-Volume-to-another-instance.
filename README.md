# Copy a deleted EC2 Instance EBS volume to a running instance

## Full Step-by-Step guide with snapshots to both describe and illustrate how I can detach an EBS volume from an EC2 Instance and load that same EBS Volume on another running instance.

### This project demonstrates how to detach an EBS volume from an instance and attach it to another running instance. This project will cover:

* Setting up two EC2 Instances

* Detaching the EBS volume from the second instance

* 

#### Instructions on how to remove an EBS volume from an instance and load it onto another running instance.


CREATE TWO EC2 INSTANCES:

* Select after typing EC2 from AWS Searchbar

* Select Instances from the navigation panel on the left

* Select Launch Instance

* Give your Instance a name

* Select Ubuntu as AMI

* Select your Keypair from the dropdown menu after scrolling down to the keypair section.

* Select Launch Instance at the bottom.

* Repeat all the same steps above, except for giving another name to this second EC2 instance.


DETACHING & DELETE THE EBS VOLUME FROM THE SECOND EC2 INSTANCE:

*Select the second EC2 Instance Created

* Select Attach from the top right of the Instances Page

* Select Storage from the drop-down options.

* Select Detach Volume.

* Select the volume you want to detach from the box that appears.

* Select the Detach Volume Button.

* Select Volume from the navigation panel on the left.

* Select Actions from the top right of the Volumes Page

* Select Delete Volume

* Type Delete into the box that appears.

* Select the Delete Button.



















##### Contribution Policy

This project is not accepting external contributions, including pull requests or feature requests.

It serves as a personal archive of my learning journey in applying foundational concepts in software development and version control. Active development is not ongoing, and external changes will not be integrated.
