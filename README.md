Role Name
=========

An example ansible roles for create instance on vultr.

Requirements
------------

- python >= 2.6

Role Variables
--------------

vr_server_name = Name for instance

vultr.ini
--------------

Place your vultr.ini in same directory level with playbook

```
[default]
key = YOUR_KEY
timeout = 60
```

Replace YOUR_KEY with your API key


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars:
        - vr_server_name: server1
      roles:
         - { role: vultr }

License
-------

GNU GPL v3


Author Information
------------------

elasyaf @ 2018



Reference
------------------

https://docs.ansible.com/ansible/2.5/modules/vr_server_module.html
