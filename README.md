# Hobo.Ansible.Common
Ansible role for my personal basic host setup

## Install Role
### Ansible Galaxy
[Ansible Galaxy](https://galaxy.ansible.com/docs/using/installing.html) can be used to install the role:
`ansible-galaxy install git+https://github.com/hobointhecorner/Hobo.Ansible.Common.git[,<branch or commit hash>]`

### Git submodule
From inside your playbook roles directory:
`git submodule add [-b <branch or tag>] https://github.com/hobointhecorner/Hobo.Ansible.Common.git`

## Variables
| Name             | Type   | Required | Default | Desctiption |
|------------------|--------|----------|---------|-------------|
| time_zone        | string | No       |         | One of [these timezone database names](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) |
| upgrade_software | bool   | No       | false   | Upgrade APT packages |
| auto_upgrade     | bool   | No       | true    | Create an automatic `apt upgrade` cron job |
