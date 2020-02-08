## Install ELK Stack with Ansible


With this playbook you can simply install ELK Stack on Vagrant virtual machines. You will install Java, Elasticsearch, Logstash, Kibana, Filebeat, Metricbeat.

Prerequisites;

- Ansible 1.2 or newer
- Vagrant 2.2 or newer
- Make your that you changed hosts file

For creating virtual machine;

    vagrant up


For running this playbook use;

    ansible-playbook -i hosts site.yml

    Then go to http://your_site_link:5601 for Kibana
