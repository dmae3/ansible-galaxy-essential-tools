Role of installing Essential tools
=========

Essential tools ansible galaxy role.

Requirements
------------

None

Role Variables
--------------

* essential_tools  
install package list.

Dependencies
------------

None

Example Playbook
----------------

```yml
---
- hosts: all
  become: true
  roles:
    - role: galaxy-essential-tools
      essential_tools:
        - name: git
          version: 1.8.3.1-6.el7_2.1
```

License
-------

BSD

Author Information
------------------

[Daisuke Maeda](https://github.com/dmae3 "Daisuke Maeda")
