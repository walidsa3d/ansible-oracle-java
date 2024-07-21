# Ansible Role: Oracle_Java

An Ansible role that installs Oracle Java on Ubuntu.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

```yaml
java_version: 21
```
# Example Playbook
To install this role, create a playbook as follows:

```yaml
---
- hosts: all
  become: yes
  roles:
    - role: oracle_java
```

Run the playbook with:

```yaml
ansible-playbook -i your_inventory_file playbook.yml
```

# License
MIT

