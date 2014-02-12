Ansible playbook to set up our community server
===============================================

This setup also uses my uwsgi role which is published in the [ansible galaxy](https://galaxy.ansible.com/).
Install it with:

    ansible-galaxy --roles-path roles install gdamjan.uwsgi


Usage:

    ansible-playbook -i hosts site.yml --sudo

Optionaly add `--ask-sudo-pass` if you need to enter a password for sudo.
