Ansible-zabbix-agent [![Ansible Galaxy](https://img.shields.io/badge/galaxy-zabbix-660198.svg)][1]
===

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
