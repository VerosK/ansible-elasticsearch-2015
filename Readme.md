# Readme

## Description

*ansible-elasticsearch* is an [Ansible](http://ansible.cc) role.
The role contains tasks to install Elasticsearch, with the Paramedic dashboard.

## Provides

1. Elasticsearch
2. possible Paramedic plugin

## Requires

1. Ansible 1.6 or higher
2. CentOS 6 || Debian 7.3

This role is based on role from ICTO

## Usage

### Get the code

```bash
$ git clone git@github.com:verosk/ansible-elasticsearch.git
```

### Create the playbook file

```
---
- name: Elasticsearch
  hosts: elasticsearch
  roles:
    - elasticsearch
```
