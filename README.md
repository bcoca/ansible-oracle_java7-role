Role Name
========

This role installs the official Oracle java7

Requirements
------------

This role requires the debconf module for Debian derived distros (included in the role and might be removed once accepted in ansible)

Role Variables
--------------

Only 1 var that you should override if you need a specific version, the default is as follows:

oracle_packages:
    - oracle-java7-installer
    - oracle-java7-set-default

Dependencies
------------

Only that you have tried using OpenJDK first.
Also you need python module pycurl installed.

License
-------

GPLv2

Author Information
------------------

briancoca+orajava@gmail.com
