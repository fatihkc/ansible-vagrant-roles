## Install Wordpress with Ansible


With this playbook you can simply install Wordpress on Vagrant virtual machines. You will install  MariaDB, Nginx and PHP-FPM for Wordpress.

Prerequisites;

- Ansible 1.2 or newer
- Vagrant 2.2 or newer


For creating virtual machine;

    vagrant up


For running this playbook use;

    ansible-playbook -i hosts site.yml

This playbook will be updated when Vagrant publishes official Centos 8 box.