OULibraries Software Collections PHP
=========

This role will:

* Install PHP 5.6 and the PHP-FPM service from Red Hat Software Collections.
* Install composer to `/opt/php/bin/composer.phar`.

PHP-FPM can be used with both Apache and Nginx, but this role doesn't
currently configure either.


Requirements
------------

No requirements beyond basic ansible. 

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

[MIT](https://github.com/OULibraries/ansible-role-sclphp/blob/master/LICENSE)

Author Information
------------------

Written for OU Libraries. 
