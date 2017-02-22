[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/grycap/ansible-role-kafka.svg?branch=master)](https://travis-ci.org/grycap/ansible-role-kafka)

InfluxDB Role
===================

Install [InfluxDB](https://www.influxdata.com/open-source/).  
This role has been tested only with Ubuntu 16. Is not ensured that it will work with other systems.

Role Variables
--------------

Variables used in this role:

	# Install info
	influxdb_version: "0.9.5"

Example Playbook
----------------
```
- hosts: server
  roles:
  - { role: 'grycap.influxdb' }
```

Contributing to the role
========================
In order to keep the code clean, pushing changes to the master branch has been disabled. If you want to contribute, you have to create a branch, upload your changes and then create a pull request.  
Thanks
