Ansible Role: Docker Compose
=========

[![Build Status](https://travis-ci.org/djx339/ansible-role-docker-compose.svg?branch=master)](https://travis-ci.org/djx339/ansible-role-docker-compose)

Install [docker-compose](https://docs.docker.com/compose/), a tool for defining and running multi-container Docker applications on Linux.

Requirements
------------

None.

Role Variables
--------------

`docker_compose_version`: The version of docker-compose. (default: latest)

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - { role: docker-compose, docker_compose_version: latest }
```

License
-------

BSD

Author Information
------------------

This role was created by [Daniel D](https://github.com/djx339).
