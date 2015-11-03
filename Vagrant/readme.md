Pre-steps

1) Download and Install Virtualbox:

        https://www.virtualbox.org/wiki/Downloads

2) Download and install vagrant.

        https://www.vagrantup.com/downloads.html

3) Install the vagrant-vbguest plugin:

   Redhat/Cent:     sudo vagrant plugin install vagrant-vbguest

4) Install ansible
	http://www.tecmint.com/install-and-configure-ansible-automation-tool-in-linux/

Creates the virtualbox and provisions
vagrant up --provider=virtualbox

Re-provision the box to stock
vagrant provision

Destroy the vagrant box
vagrant destroy

Supsend the vagrant box
vagrant suspend

Resume the vagrant box
vagrant resume



reach site at
http://local.dev.copperleafworkshop.com:8888/
