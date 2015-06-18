Ansible aliases Role
====================
[![Build Status](https://semaphoreci.com/api/v1/projects/b3e554f7-8f61-4915-beac-742e99242fd7/459414/badge.svg)](https://semaphoreci.com/michaelrigart/ansible-role-aliases) [![Build Status](https://travis-ci.org/michaelrigart/ansible-role-aliases.svg?branch=master)](https://travis-ci.org/michaelrigart/ansible-role-aliases)

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