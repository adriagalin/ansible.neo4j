adriagalin.neo4j
================

[![Build Status](https://travis-ci.org/adriagalin/ansible.neo4j.svg?branch=master)](https://travis-ci.org/adriagalin/ansible.neo4j) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-neo4j-blue.svg)](https://galaxy.ansible.com/list#/roles/NUM)

An ansible role for set up a Neo4j graph database server.

Requirements
------------

Tested on:

-	Ubuntu 14.04 LTS
-	Ubuntu 16.04 LTS

Should work with:

-	All Ubuntu
-	All Debian

Role Variables
--------------

Check defaults/main.yml file to review all vars.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
    - hosts: all
      roles:
        - { role: adriagalin.neo4j }

License
-------

GPLv3 License.

Author Information
------------------

[Adrià Galín](https://www.adriagalin.com/)

Inspiration
-----------

During development, some roles in Ansible Galaxy/Github also inspired me:

-	[julienroubieu](https://github.com/julienroubieu/ansible-neo4j)
-	and many others.

thank you.