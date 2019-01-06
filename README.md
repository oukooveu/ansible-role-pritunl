Ansible role: Pritunl
=========

Install Pritunl VPN server and MongoDB for RedHat/CentOS and Debian/Ubuntu.

Requirements
------------

None.

Role Variables
--------------

```
mongo_version: "4.0"
mongo_component: "main"
```

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - pritunl
```

License
-------

Apache 2.0

Author Information
------------------

Daniil Kupchenko, kupchenko@gmail.com
