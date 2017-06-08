andrewrothstein.cntlm
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-cntlm.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-cntlm)

Builds and installs [CNTLM](http://cntlm.sourceforge.net/)

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
    - andrewrothstein.cntlm
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
