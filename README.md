[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/grycap/ansible-role-kafka.svg?branch=master)](https://travis-ci.org/grycap/ansible-role-kafka)

InfluxDB Role
===================

Install InfluxDB (Only working for Ubuntu 16)

Role Variables
--------------

The variables that can be passed to this role and a brief description about them are as follows.

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
