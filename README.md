andrewrothstein.rolename
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-rolename.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-rolename)

Configures Nexus. Assumes Nexus is already installed. See andrewrothstein.nexus-repo.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.rolename
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
