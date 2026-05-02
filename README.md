# Ansible Roles & Galaxy Lab

## Overview
This project demonstrates how to build reusable Ansible roles and use Ansible Galaxy community roles in a single automation workflow.

## Technologies Used
- Ansible Core
- Ansible Galaxy
- Nginx
- MySQL
- Ubuntu Linux

## Project Structure

- Custom reusable Nginx role
- Community MySQL role from Ansible Galaxy
- Inventory management
- Multi-playbook orchestration

## Features

### Nginx Role
- Install Nginx
- Deploy custom nginx.conf using Jinja2 template
- Create index page
- Enable and start service
- Restart handler when config changes

### MySQL Role
- Install MySQL using Galaxy role
- Configure root password
- Create database: appdb
- Create user: appuser

## Run Project

```bash
ansible-galaxy install -r requirements.yml
ansible-playbook site.yml



Results
Nginx deployed successfully
MySQL configured successfully
Playbook completed with failed=0
Screenshots

See /screenshots folder.

Author

Habiba Mohamed Megahed Abdeleal
