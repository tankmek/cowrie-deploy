# cowrie-deploy
Deploys a Cowrie Honeypot.

## Requirements
`Ansible >= 2.8`

## Tested On
`Debian 10`

## Usage:
```
ansible-playbook site.yml
```
## Role Variables

This role has multiple variables.
The descriptions and defaults for all these variables can be found in the **defaults/** folder of this role:

| Name | Description |
| ---- | ----------- |
| **[`main.yml`](https://github.com/tankmek/cowrie-splunk-deploy/group_vars/honeypots/cowrie.yml)** | Cowrie Honeypot variables |

# Notes
Debian systems need python3-venv and python3-virtualenv
