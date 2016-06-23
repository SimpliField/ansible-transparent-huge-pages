Disable transparent huge pages
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
  - { role: SimpliField.tranparent-huge-pages }
```

License
-------

BSD
