ansible-layout-cockroachdb.yml
==============================

Use this ansible layout to deploy cockroachdb in standalone only.

Requirements
------------

ansible >= 2.5
Debian 8

Ansible Role
------------
https://github.com/hollardjf/ansible-role-cockroachdb

Setup
-----
```
$> ./bin/git.sh
```
Copy and update inventories/local-standalone according to inventories/<your-inventory>

Deploy
------
```
$> ./bin/install.sh inventories/<your-inventory>/hosts
```

FYI
---
https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html#directory-layout