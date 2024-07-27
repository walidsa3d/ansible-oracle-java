# Ansible Role: Oracle_Java

An Ansible role that installs Oracle Java on Ubuntu.
![Ansible Role](https://img.shields.io/ansible/role/d/walidsa3d/oracle_java)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/walidsa3d/ansible-oracle-java/main.yml)

Install
------------
```
ansible-galaxy role install walidsa3d.oracle_java

```
Requirements
------------

None.

Role Variables
------------

Available variables are listed below, along with default values:

```yaml
java_version: 21
```

Example Playbook
------------
To use this role, create a playbook as follows:

```yaml
---
- hosts: all
  become: yes
  roles:
    - role: walidsa3d.oracle_java
```

# License
MIT

