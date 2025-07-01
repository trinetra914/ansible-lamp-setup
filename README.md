# Ansible LAMP Stack Setup

This project uses Ansible to install and configure a full LAMP stack (Linux, Apache, MySQL, PHP) on two Ubuntu-based virtual machines.

## Features
- Apache2 installation and setup
- MySQL Server setup
- PHP installation
- PHP info page deployment

## Inventory
Hosts:
- 192.168.0.117 (server1)
- 192.168.0.118 (server2)

## Usage
```bash
ansible-playbook -i hosts site.yml --ask-become-pass
