Ansible-zabbix-agent [![Ansible Galaxy](https://img.shields.io/badge/galaxy-zabbix--agent-660198.svg)][1]
===

[![Debian](https://img.shields.io/badge/platform-debian-red.svg)]()
[![Ubuntu](https://img.shields.io/badge/platform-ubuntu-orange.svg)]()

> Install zabbix-agent on debian/ubuntu servers.

Requirements
---

- Ansible >= 2.2.1

Example Playbook
---

```
- hosts: localhost
  vars:
    - zabbix_version: 3.4
    - zabbix_server: zabbix.example.com
    - zabbix_agent_hostname: "custom_hostname" # (optional)

  roles:
    - role: zabbix-agent
```

License
---

GNU GPL v3.0

**Free Software, Hell Yeah!**

[1]: https://galaxy.ansible.com/ston3o/zabbix-agent/
