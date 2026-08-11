# Ansible build of ruru jails for Postgresql, Nextcloud and Kanboard

## Source files
~/Documents/Bin/Ansible/ruru/ansible-bastille-jails/

## Execution

Run the complete deployment with:

``ansible-playbook site.yml --ask-vault-pass'``

To target a single service after initial creation (e.g., updating PostgreSQL settings inside its jail):

``ansible-playbook site.yml --limit postgres-new'``

