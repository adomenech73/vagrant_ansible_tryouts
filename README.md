## vagrant_ansible_tryouts
------------------------------------------------------------------------------
This are my tryouts with ansible using vagrantfiles to deploy any provision some development environments

Initial requirements:

 - Vagrant 1.7.4
 - Ansible 1.2
 - vbox CentOS 7

## Installing requirements

```bash
wget https://dl.bintray.com/mitchellh/vagrant/vagrant_1.7.4_x86_64.deb
sudo dpkg -i vagrant_1.7.4_x86_64.deb

sudo pip install ansible

vagrant box add centos7-base  https://github.com/holms/vagrant-centos7-box/releases/download/7.1.1503.001/CentOS-7.1.1503-x86_64-netboot.box

cd lamp && vagrant up

cd mean && vagrant up

```