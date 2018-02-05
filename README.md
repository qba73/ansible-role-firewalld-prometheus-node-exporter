Role Name
=========

Ansible role for configuring service Prometheus Node Exporter

Requirements
------------

Firewalld service up and running.

Role Variables
--------------

n/a

Dependencies
------------

n/a

Example Playbook
----------------

Example of how to use the role: 

    - hosts: all
      roles:
         - { role: firewalld-prometheus-node-exporter, port: 9100 }


Author Information
------------------

[Jakub Jarosz](https://twitter.com/qba73)



