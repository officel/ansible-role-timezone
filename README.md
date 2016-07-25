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

zonename are...

     # CentOS 6
     $ ls /usr/share/zoneinfo/

     # CentOS 7
     $ timedatectl list-timezones

Dependencies
------------

none.

Example Playbook
----------------

    - hosts: all
      become: yes
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
