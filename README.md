<DOCKER_APP_NAME>
=================

![test status](https://github.com/bsmeding/ansible_role_nautobot_docker/actions/workflows/ci.yml/badge.svg) 
Role is tested on, Ubuntu with Docker installed via my role bsmeding.docker on Linux distribution.

Nautobot is an network CMDB tool created for and by network automation specialist from NetworkToCode. It is an fork from Netbox (2.x) and added with a lot af nice features to create a Single Source of Trouth for your automation platform.

This role will install Nautobot as docker container. If you need docker aswell, so you can build the whole application at once please consider the Ansible role [bsmeding.docker](https://galaxy.ansible.com/ui/standalone/roles/bsmeding/docker/) that will prepare you're server and install docker.


VARIABLES
=========

Without customizing anything this role wil install the app will all it's default settings, see `defaults/main.yml`
To change anything, see the following list of  variables that can be adjusted:

Default docker role variables
-----------------------------
Default variables that exist in all of my Ansible docker roles, but for each role named differently.


| variable name | default value | description                               |
|---------------|---------------|-------------------------------------------|
|               |               |                                           |


App specific variables
----------------------

See the following table for app specific variables


| variable name | default value | description                               |
|---------------|---------------|-------------------------------------------|
|               |               |                                           |




