Ansible Role: timezone
=========

[![Build Status](https://travis-ci.org/officel/ansible-role-timezone.svg?branch=master)](https://travis-ci.org/officel/ansible-role-timezone)
[![Ansible Role](https://img.shields.io/badge/galaxy-officel.timezone-blue.svg?maxAge=2592000)](https://galaxy.ansible.com/officel/timezone/)

set(init) timezone. default Asia/Tokyo.

Requirements
------------

none.

Role Variables
--------------

none.

Dependencies
------------

none.

Example Playbook
----------------

    - hosts: all
      roles:
         - officel.timezone

         or

         - {role: officel.timezone,
            zonename: "Asia/Tokyo"
           }

License
-------

MIT / BSD

Author Information
------------------

This role was created by raki.
