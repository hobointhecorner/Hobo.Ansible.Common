# Hobo.Ansible.Common
Ansible role for my personal basic host setup

## Install Role
From inside your playbook roles directory:
`git submodule add [-b <branch or tag>] https://github.com/hobointhecorner/Hobo.Ansible.Common.git`

## Variables
| Name             | Type   | Required | Default | Desctiption |
|------------------|--------|----------|---------|-------------|
| upgrade_software | bool   | No       | false   | Upgrade APT packages |
| auto_upgrade     | bool   | No       | true    | Create an automatic `apt upgrade` cron job |
