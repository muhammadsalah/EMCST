# EM CST 2019 Studio -- Student Version
The repository is a vagrant box for student version for CST Studio 2019

# System Pre-reqs

The setup will run a virtual machine with the following configurations:

* CPU Cores: 2
* Memory: 4GB
* Storage: 80 GB Compact VMDK

# Required Software

The setup leverages the virtualization of "Oracle VirtualBox".

Download from this URL: https://www.virtualbox.org/wiki/Downloads

**Make sure to install the guest addtions**

Vagrant automates the operation of the provider "VirtualBox".

Download from this URL: https://www.vagrantup.com/downloads.html

# Usage

Simply clone this repository

    git clone https://github.com/muhammadsalah/EMCST.git
    
or download as ZIP and extract it.

Run the command inside the directory
    
    vagrant up
    
It will create a VM named 'cst-windows' with the mentioned configuration above.

You can customize the configurations to increase the RAM or CPU assigned as well
by using modifying the vagrant file in the bottom section memory and cpus properties.

# Notice
You need to register for student license for CST and insert your email to activate the upon
using the software.

# Credentials

**Username** vagrant
**Password** vagrant
