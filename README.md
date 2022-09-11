[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Ftankmek%2Fcowrie-deploy&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

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
