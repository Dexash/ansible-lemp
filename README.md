# Ansible LEMP playbook

Ansible playbook for personal use. Installs full LEMP stack for testing/developing purposes

## Requirements

1. `python-dev` 
2. `python-pip`
3. `python-openssl`
4. `ansible`

## Setup

### Install ansible & dependencies

1. `Chmod +x setup_ansible.sh`
2. `sudo ./setup_ansible.sh`

## Roles

- common
- nginx
- mysql
- php7.0
- composer
- phpmyadmin

## Usage

- `$ ansible-playbook -i hosts/testing master.yml --ask-become-pass`



