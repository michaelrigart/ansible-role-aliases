Ansible aliases Role
====================
[![Build Status](https://travis-ci.org/michaelrigart/ansible-role-aliases.svg)](https://travis-ci.org/michaelrigart/ansible-role-aliases)

An ansible role for managing mail aliases

Role Variables
--------------

    aliases_list: a list of dictionaries holding the user and the alias
        - user: postmaster
          alias: root

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: MichaelRigart.aliases }

License
-------

GPLv3

Author Information
------------------

Michaël Rigart <michael@netronix.be>