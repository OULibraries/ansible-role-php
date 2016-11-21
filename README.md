OULibraries.sclphp
=========

Install PHP 5.6 and PHP-FPM service for use with Apache and Nginx from Red Hat Software Collections. 

Requirements
------------

Currently none. 

Role Variables
--------------

Currently none. 

Dependencies
------------

Probably depends on OULibraries.centos.

Example Playbook
----------------

```yaml
- hosts: lamp.vagrant.localdomain
  sudo: yes
  roles:
    - role: OULibraries.sclphp
      tags: php
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
