# Nodejs provisioning on Debian/Ubuntu

## How to use:

1. Edit Nodejs version in defaults/main.yaml or in the nodejs.yaml playbook

2. nodejs.yaml - playbook:

---
- hosts: all.
  gather_facts: true
  become: true
  roles:
  - ansible-nodejs
  vars:
    nodejs_version: 10.x

3. Run ansible-playbook:

```
ansible-playbook -i hosts nodejs.yaml
```
