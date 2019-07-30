Role Name
=========

Install Kubectl plugin Krew in /usr/local/bin/

Requirements
------------

You need to have Kubectl installed.

ansible-galaxy install andrewrothstein.kubectl

Role Variables
--------------

Defaults
krew_version: Sets the Krew version


Dependencies
------------

Ansible Galaxy
andrewrothstein.kubectl

Example Playbook
----------------

Example use of Kubectl Krew role

- hosts: localhost

  roles:
    - role: andrewrothstein.kubectl
    - role: kubectl_krew

License
-------

GPLv3

Author Information
------------------

Christian Nygaard
