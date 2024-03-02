# Ansible Init Server

## Overview
`ansible-init-server` is an Ansible playbook is to automate the process of initializing new servers with basic security configurations.

## Covers
- **SSH Hardening**: Configures SSH to disable root login and password authentication, opting for key-based authentication.
- **User Management**: Automates the creation of an ansible user and a personal user.
- **Security Updates**: Ensures that the server is up-to-date with the latest security patches.

## Requirements
- Ansible 2.9 or higher.
- Access to the target server(s) via SSH.
- Sudo privileges on the target server(s).

## Getting Started
1. **Clone the Repository**:

2. **Configuration**:
Edit the `inventory.ini` file to add your server's IP address and modify any variables in `vars/main.yml` to suit your needs.

4. **Run the Playbook**:
