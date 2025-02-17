# Virtual Machine Automation with Vagrant


## Download a virtual machine (Virtual box, etc):

Link: 
https://www.virtualbox.org/wiki/Downloads
    
    choco install virtualbox

## Install Vragant Manager
    
### Windows

    choco install vagrant

### MacOS
    brew install --cask virtualbox (No para MacOs M1)

    brew install --cask vagrant
    
    brew install --cask vagrant-manager


## Generate VagrantFile
####  Create a directory and generate vagrant file:

    mkdir carpeta

    Get dependecy link from Vagrant Cloud: 
    https://portal.cloud.hashicorp.com/vagrant/discover/geerlingguy/centos7


    vagrant init geerlingguy/centos7 --box-version 1.2.27

## Update VagrantFile depedencies / Init VM
    vagrant up

## Close generated virtual machine
    vagrant halt


## Delete VM
    vagrant destroy





