Ansible Role Win Restic
=========

Installs Restic backup utility
https://github.com/restic/restic/releases


Example Playbook
----------------

```yaml
- hosts: servers
  roles:
      - { role: ansible-role-win-restic, restic_version: '0.10.0' }
```


