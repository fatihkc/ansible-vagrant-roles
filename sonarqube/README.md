## Install SonarQube with Ansible


With this playbook you can simply install SonarQube on Vagrant virtual machines. You will install Java 11, PostgreSQL 12 and SonarQube 8.1.

Prerequisites;

- Ansible 1.2 or newer
- Vagrant 2.2 or newer
- Make your that you changed hosts file

For creating virtual machine;

    vagrant up


For running this playbook use;

    ansible-playbook -i hosts site.yml

    Then go to http://your_site_link:9000/sonar for SonarQube.
