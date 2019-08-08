ggr role
=========
[![License](https://img.shields.io/badge/license-Apache-green.svg?style=flat)](https://raw.githubusercontent.com/lean-delivery/ansible-role-ggr/master/LICENSE)
[![Build Status](https://travis-ci.org/lean-delivery/ansible-role-ggr.svg?branch=master)](https://travis-ci.org/lean-delivery/ansible-role-ggr)
[![Build Status](https://gitlab.com/lean-delivery/ansible-role-ggr/badges/master/pipeline.svg)](https://gitlab.com/lean-delivery/ansible-role-ggr/pipelines)
[![Galaxy](https://img.shields.io/badge/galaxy-lean__delivery.ggr-blue.svg)](https://galaxy.ansible.com/lean_delivery/ggr)
![Ansible](https://img.shields.io/ansible/role/d/42600.svg)
![Ansible](https://img.shields.io/badge/dynamic/json.svg?label=min_ansible_version&url=https%3A%2F%2Fgalaxy.ansible.com%2Fapi%2Fv1%2Froles%2F42600%2F&query=$.min_ansible_version)

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should
be mentioned here. For instance, if the role uses the EC2 module, it may be a
good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including
any variables that are in defaults/main.yml, vars/main.yml, and any variables
that can/should be set via parameters to the role. Any variables that are read
from other roles and/or the global scope (ie. hostvars, group vars, etc.) should
be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in
regards to parameters that may need to be set for other roles, or variables that
are used from other roles.

Example Playbook
for packer
---
- name: install
  hosts: all
  gather_facts: no
  roles:
    - { role: ../ansible-role-ggr, become: true }
---
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-ggr }

License
-------
Apache

Author Information
------------------

authors:
  - Lean Delivery Team <team@lean-delivery.com>
