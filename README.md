Disable transparent huge pages [![Build Status](https://travis-ci.org/SimpliField/ansible-transparent-huge-pages.svg?branch=master)](https://travis-ci.org/SimpliField/ansible-transparent-huge-pages) [![Ansible Role](https://img.shields.io/ansible/role/10479.svg?maxAge=2592000)](https://galaxy.ansible.com/SimpliField/transparent-huge-pages/)
=========

Disable transparent huge pages

https://docs.mongodb.com/manual/tutorial/transparent-huge-pages/

Requirements
------------

Need ansible 2+

Role Variables
--------------

```yaml
```

Dependencies
------------

There is no dependency

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - { role: SimpliField.transparent-huge-pages }
```

License
-------

BSD
