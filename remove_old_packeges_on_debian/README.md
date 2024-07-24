Role Delete Debian old packeges
================

Example Playbook
----------------
```
hosts: all
become: yes
roles:
  - role: remove_old_packeges_on_debian
    vars:
      old_packeges:
        - libdns-export1104
```
License
----------------

BSD

