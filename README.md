Ansible Nfs Client
=========

* Galaxy: [![Ansible Galaxy](https://img.shields.io/badge/galaxy-tcharl.nfs_client-660198.svg?style=flat)](https://galaxy.ansible.com/tcharl/nfs_client)
* Lint & requirements: ![Molecule](https://github.com/OsgiliathEnterprise/nfs_client/workflows/Molecule/badge.svg)
* Tests: [![Build Status](https://travis-ci.com/OsgiliathEnterprise/nfs_client.svg?branch=master)](https://travis-ci.com/OsgiliathEnterprise/nfs_client)
* Chat: [![Join the chat at https://gitter.im/OsgiliathEnterprise/platform](https://badges.gitter.im/OsgiliathEnterprise/platform.svg)](https://gitter.im/OsgiliathEnterprise/platform?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Wrapper on top of Ansible freeipa server to configure automount on NFS client with Kerberos

Requirements
------------

Like any other platform role, executing `tox -e pipdep` and `tox -e dependency` 

Role Variables
--------------

Take a look at the [molecule tests](./molecule/default/converge.yml) tests and the [default variables](./defaults/main.yml)

Dependencies
------------

* Every collection listed in [requirement collections](./requirements-collections.yml) 
* Every role listed in [requirement](./requirements-standalone.yml)

License
-------

[Apache-2](https://www.apache.org/licenses/LICENSE-2.0)

Author Information
------------------

* Twitter [@tcharl](https://twitter.com/Tcharl)
* Github [@tcharl](https://github.com/Tcharl)
* LinkedIn [Charlie Mordant](https://www.linkedin.com/in/charlie-mordant-51796a97/)
