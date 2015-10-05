# devstackKilo
Vagrant setup for a Kilo Devstack setup running on Ubuntu 14.04

Prerequisites:
1) Vagrant  (https://www.vagrantup.com/)
2) VirtualBox (https://www.virtualbox.org/wiki/Downloads)

To Use/Launch:
1. Clone this repo
2. Edit the local.conf file for any Devstack specific settings you want to use 
  - Pay close attention to the HOST_IP choice as it should match the Vagrantfile
3. Edit the Vagrantfile for any specific settings you want to change
  - Pay close attention to the "private_network" setting as that should match HOST_IP from step 2
4. vagrant up

What happens?
1. vagrant will download an Ubuntu 14.04 box
2. vagrant will launch the box and apply the provisioning step to get devstack/configure/launch devstack
3. You will end up with a fully running Kilo Devstack environment!  
4. Welcome to OpenStack!



