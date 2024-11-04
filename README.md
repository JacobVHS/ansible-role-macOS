# ansible-role-macOS

## Installation
```shell
ansible-galaxy install jacobvhs.unix_conf_management
```

## Usage Example
```yaml
---
- name: Config Manage MacOS for Jacob
  hosts: localhost
  vars:
    username: "jacobschreuder"
  roles:
    - jacobvhs.

```
```shell
ansible-playbook playbook.yaml
```

## Author
Jacob Schreuder