setup_aci
=========

Basic configuration of ACI

Requirements
------------

Requires the Cisco.Aci collection.

Role Variables
--------------

Configuration parameters are included in vars/main.yml

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- name: "Create basic ACI setup"
  hosts: "apic"
  connection: local
  gather_facts: no

  roles:
  - role: setup_aci


License
-------

GNU GENERAL PUBLIC LICENSE

Author Information
------------------

Aria Givi <ariagivi@yahoo.de>
