Role Name
=========

An example ansible roles for create instance on vultr.

Requirements
------------

- python >= 2.6

Role Variables
--------------

vr_server_name = Name for instance


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

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
