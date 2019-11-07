Ansible Role: Memcached
=========

Ansible Role to install Memcached on RHEL/CentOS 

Requirements
------------

None

Role Variables
--------------
The following variables are defined in the is role with there default values.
```
mcached_port: 11211
mcached_ip: 127.0.0.1
mcached_memory_limit: 64
mcached_connections: 1024
mcached_log_file: /var/log/memcached.log
mcached_log_verb_level: ""
```

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cyberitas.ansible_role_memcached }

License
-------

MIT

Author Information
------------------

Created in 2019 by James Dugger for Cyberitas Technologoies, LLC
