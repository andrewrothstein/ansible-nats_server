andrewrothstein.nats_server
=========
![Build Status](https://github.com/andrewrothstein/ansible-nats_server/actions/workflows/build.yml/badge.svg)

Installs [nats-server](https://github.com/nats-io/nats-server).

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
    - andrewrothstein.nats_server
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
