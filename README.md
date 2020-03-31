backup-sw-config
=========

With this role you can perform backup of the configurations of your Cisco equipments with IOS.

Requirements
------------

Role tested in Ansible 2.9.2, Python 2.7, Cisco IOS

Dependencies
------------

This role depends that a user that do login into switch and already been at enable mode. Otherwise you will need use ansible_become and ansible_become_method like this: https://docs.ansible.com/ansible/latest/network/user_guide/network_best_practices_2.5.html

Example Playbook
----------------

```
- name: Making backup
  hosts: your_inventory
  roles:
    - backup-sw-config
```

License
-------

BSD

Author Information
------------------

Github: [vinealvees](#https://github.com/vinealvees/)