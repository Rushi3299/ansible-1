Nexus OSS
==========

Ansible role installs Docker container with NExus OSS

Requirements
------------

Docker running on target host

Role Variables
--------------

see [./defaults/main.yml](./defaults/main.yml)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: servers
  roles:
    - role: ussrlongbow.nexus
      nexus_bind_addr: '192.168.0.2'
```

License
-------

[MIT License](./LICENSE)
