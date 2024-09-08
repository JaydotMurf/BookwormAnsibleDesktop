# Ansible Setup for Debian Machines

![Project Logo](assets/logo.png)

This repository automates the installation and configuration of my favorite tools on Debian machines.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/JaydotMurf/debian-ansible-setup.git
   cd ansible-setup
   ```

2. Run the playbook:
   ```bash
   ansible-playbook playbooks/setup.yml --ask-become-pass
   ```

## Playbooks

- `setup.yml`: Orchestrates all tasks.
- `install_software.yml`: Installs the required software.
- `configure_dotfiles.yml`: Deploys dotfiles to the machine.
