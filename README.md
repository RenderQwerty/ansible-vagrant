# Ansible role for Vagrant

This role will configure your server with vagrant.

# Usage example
    ansible-galaxy install renderqwerty.ansible_galaxy_vagrant

Add this to your playbook:

    - name: Setup for vagrant boxes
      hosts: all
      sudo: yes
      gather_facts: true
      roles:
        - renderqwerty.ansible_galaxy_vagrant

# License

MIT License

# Author

Yurii Fisakov
