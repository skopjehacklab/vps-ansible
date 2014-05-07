Ansible playbook to set up our community server
===============================================

This setup also uses my uwsgi role which is published in the [ansible galaxy](https://galaxy.ansible.com/).
Install (or update) it with:

    ansible-galaxy install gdamjan.uwsgi --force


Usage:

    ansible-playbook site.yml

Optionaly add `--ask-sudo-pass` if you need to enter a password for sudo.
