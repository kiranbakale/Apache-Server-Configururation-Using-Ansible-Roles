Role Name
=========

Apache Web Server Configuration Using Ansible Roles in RHEL/CentOS.

Requirements
------------

Ansible must be installed in control node and there must be passwordless authentication setup with client nodes where you want to deploy webserver.

Role Variables
--------------

Make sure that the hosts group is defined in the inventory file i.e. /etc/ansible/hosts and make the changes in the apache.yml file for your hosts group name before running it. Also don't forget to replace the existing index.html file with you own file which you want to host on webserver in files directory under apache.

Dependencies
------------

Ansible must be installed in control node and there must be passwordless authentication setup with client nodes where you want to deploy webserver.
Make sure that the hosts group is defined in the inventory file i.e. /etc/ansible/hosts and make the changes in the apache.yml file for your hosts group name before running it. Also don't forget to replace the existing index.html file with you own file which you want to host on webserver in files directory under apache.

Example Playbook
----------------

Clone this repository in your machine and go to apache directory. The default Ansible Roles location is /etc/ansible/roles/, use following command to go to apache directory.
cd /etc/ansible/roles/apache
To run the roles to configure apache on client nodes just run the apache.yml file using below command.
ansible-playbook -v apache.yml

License
-------

BSD

Author Information
------------------
Vikas Nehra (Nehra Classes)
https://www.youtube.com/NehraClasses?sub_confirmation=1
An optional section for the role authors to include contact information, or a website (HTML is not allowed).
# Apache-Server-Configururation-Using-Ansible-Roles
