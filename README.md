Ansible Role | Template
=========
[![Build Status](https://travis-ci.org/arnobirchler/ansible-role-nginx-new-vhost.svg?branch=master)](https://travis-ci.org/arnobirchler/ansible-role-nginx-new-vhost)

Empty role with travis-ci configuration

Requirements
------------

```
- arnobirchler.nginx
```

Role Variables
--------------

```
- php_version: 
- redirect_domain: domain.com
- domain: "domain.com"
- domain_alias: "shop.domain.com back.domain.com"
```

Dependencies
------------

Ansible : No dependencies

Travis : 2 Depedencies
  - [Github gist](https://gist.github.com/arnobirchler/627e4655465b696a0b521a560bc2206f)
  - [Docker images](https://hub.docker.com/r/arnobirchler/docker-os-ansible/)

Example Playbook
----------------
```
- name: "FILE | create a file"
  file:
    path: "./test.txt"
    state: touch
```

License
-------

MIT

Author Information
------------------

Arno Birchler
