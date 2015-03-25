Ansible aliases Role
====================
[![Build Status](https://travis-ci.org/michaelrigart/ansible-role-aliases.svg)](https://travis-ci.org/michaelrigart/ansible-role-aliases)

An ansible role for managing mail aliases

Role Variables
--------------

```yaml
aliases_list: a list of dictionaries holding the user and the alias
    - user: postmaster
      alias: root
```

Example Playbook
-------------------------

```yaml
- hosts: servers
  roles:
     - { role: MichaelRigart.aliases, sudo: Yes }
```

License
-------

GPLv3

Author Information
------------------

Michaël Rigart <michael@netronix.be>