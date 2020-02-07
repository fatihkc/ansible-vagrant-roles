## Install Jenkins with Ansible


With this playbook you can simply install Jenkins on Vagrant virtual machines. You will install Java and Jenkins packages.

Prerequisites;

- Ansible 1.2 or newer
- Vagrant 2.2 or newer


For creating virtual machine;

    vagrant up


For running this playbook use;

    ansible-playbook -i hosts site.yml

    Then go to http://your_site_link:8080

At the end of the script, your initialAdminPassword will be printed to your terminal. Use it for accessing Jenkins.
