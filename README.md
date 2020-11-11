Role Name
=========

Ansible role for deploying and configuring a one node Consul server on RH based distributions

Requirements
------------

N/A

Role Variables
--------------

CONSUL_CONFIG - configuration file for Consul, only contains minimum settings
CONSUL_SERVICE - systemd service file for Consul

Dependencies
------------

N/A

Example Playbook
----------------


    - hosts: servers
      roles:
         - j0rdan0.consul

License
-------

BSD

Author Information
------------------

https://github.com/j0rdan0

https://acidburn.me

@j0rdan0 (Twitter)
