Role Delete Debian old packeges
================

Example Playbook
----------------

  - name: Delete old packeges on debian
    hosts: all
    become: yes
    roles:
      - { role: remove_old_packeges_on_debian, when: ansible_distribution == "Debian" }

License
----------------

BSD

