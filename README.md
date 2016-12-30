Ansible aliases Role
====================

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
     - { role: MichaelRigart.aliases, become: true }
```

License
-------

GPLv3

Author Information
------------------

Michaël Rigart <michael@netronix.be>
