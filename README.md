# Nodejs provisioning on Debian/Ubuntu

## How to use:

1. Edit Nodejs version in vars/main.yaml

2. nodejs.yaml - playbook:

...  ---
...  - hosts: all
...    gather_facts: true
...    become: true
...    roles:
...    - ansible-nodejs


3. Run ansible-playbook:

```
ansible-playbook -i hosts nodejs.yaml
```
