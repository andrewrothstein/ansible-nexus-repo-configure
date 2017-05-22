andrewrothstein.nexus-repo-configure
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-nexus-repo-configure.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-nexus-repo-configure)

Configures [Nexus](http://www.sonatype.org/nexus/). Assumes Nexus is already installed. Consider [andrewrothstein.nexus-repo](https://galaxy.ansible.com/andrewrothstein/nexus-repo/).

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
    - andrewrothstein.nexus-repo-configure
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
