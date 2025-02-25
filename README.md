## Ansible Demo: Server Setup with Nginx & GitHub Repo

This project demonstrates an Ansible playbook that:
- Updates the server
- Installs Nginx
- Clones a GitHub repository

### Requirements
- Ansible installed
- SSH access to target server(s)
- Inventory file with server details

### Usage:
*Run the playbook*

`ansible-playbook -i inventory playbook.yml`

### What This Playbook Does;
- Updates package lists
- Installs Nginx
- Clones a GitHub repository
