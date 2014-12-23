apache
======

An [Ansible](http://www.ansible.com) role for the [apache HTTP server](http://httpd.apache.org).

[![Build Status](https://travis-ci.org/ansiblebit/apache.svg?branch=master)](https://travis-ci.org/ansiblebit/apache)

Requirements
------------

- ansible >= 1.4.5

Role Variables
--------------

- defaults/main.yml
- vars/main.yml

Dependencies
------------

- none

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansiblebit.apache }

License
-------

BSD

Author Information
------------------

- [steenzout](http://github.com/steenzout)
