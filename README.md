[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-MariaDB-blue.svg)](https://galaxy.ansible.com/wluisaraujo/mariadb) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-mariadb.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-mariadb)

---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [MariaDB](https://mariadb.org)
------------

Description
------------

 * Ansible role for MariaDB
 
Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.mariadb
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
  vars:
    - name: value
  roles:
    - mariadb
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
