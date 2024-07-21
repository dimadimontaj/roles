auditd_install
=========

Example Playbook
----------------
```
- name: Install and cofigure auditd
  hosts: all
  become: yes
  roles:
    - { role: auditd_install, when: ansible_distribution == "Debian" }
```
License
-------

BSD

