## Install NextCloud 18 with Ansible


With this playbook you can simply install SonarQube on Vagrant virtual machines. You will install Php, MariaDB, Nginx and NextCloud.

Prerequisites;

- Ansible 1.2 or newer
- Vagrant 2.2 or newer
- Make your that you changed hosts file

For creating virtual machine;

    vagrant up


For running this playbook use;

    ansible-playbook -i hosts site.yml

    Then go to http://your_site_link for NextCloud.
