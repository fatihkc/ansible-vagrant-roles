## Install Prometheus and Grafana with Ansible

With this playbook you can simply install Prometheus and Grafana on Vagrant virtual machines. You will install Prometheus 2.16, node_exporter 0.18 and Grafana 6.2.

Prerequisites;

- Ansible 1.2 or newer
- Vagrant 2.2 or newer
- Make your that you changed hosts file

For creating virtual machine;

    vagrant up


For running this playbook use;

    ansible-playbook -i hosts site.yml

    Then go to http://your_site_link:3000 for Grafana.
