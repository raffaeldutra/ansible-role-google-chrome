Google Chrome
=============

[![Ansible Galaxy](https://img.shields.io/badge/galaxy-nginxinc.nginx-5bbdbf.svg)](https://galaxy.ansible.com/ansible_role_google_chrome)
[![Build Status](https://travis-ci.org/nginxinc/ansible-role-nginx.svg?branch=master)](https://travis-ci.org/ansible_role_google_chrome)

Simple installation for Google Chrome.

Requirements
------------

```yaml
CentOS:
  versions:
    - 7
Debian:
  versions:
    - jessie
    - stretch
    - buster
Ubuntu:
  versions:
    - xenial
    - bionic
    - disco
```

Role Variables
--------------

```yaml
version=45.0.2454.101-1
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: localhost
  roles:
    - { role: raffaeldutra.google_chrome }
```

License
-------

BSD

Author Information
------------------

[Rafael Dutra](https://github.com/raffaeldutra)