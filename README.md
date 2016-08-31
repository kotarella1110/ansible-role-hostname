Ansible Role: Hostname
=========

[![Build Status](https://travis-ci.org/kotarella1110/ansible-role-hostname.svg?branch=master)](https://travis-ci.org/kotarella1110/ansible-role-hostname)

This role to manage hostname.

Requirements
------------

None.

Role Variables
--------------

```
hostname_fqdn: "{{ ansible_fqdn }}"
hostname_name: "{{ ansible_hostname }}"
```

Dependencies
------------

None.

Example Playbook
----------------

```
- hosts: servers
  roles:
     - { role: kotarella1110.hostname }
```

License
-------

MIT

Author Information
------------------

This role was created in 2016 by Kotaro Sugawara.
