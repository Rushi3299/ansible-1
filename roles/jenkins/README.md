[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-Jenkins-blue.svg)](https://galaxy.ansible.com/wluisaraujo/jenkins) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-jenkins.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-jenkins)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Jenkins](https://jenkins.io)
------------

Description
------------

 * [Ansible](https://www.ansible.com) for [Jenkins](https://jenkins.io)

Requirements
------------

 *

Installation
------------

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.jenkins
vagrant@localhost:~$ ansible-galaxy install -r wluisaraujo.jenkins/requirements.txt
```

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
    vars_files:
    - vars/main.yml
  roles:
    - jenkins
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
