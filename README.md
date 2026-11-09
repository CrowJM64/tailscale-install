# Ansible Role for installing Tailscale
**Author/Maintainer:** Josh Murphy

This role can either be paried with my headscale-install role, or used alone to join Ansible managed machines to a Headscale or Tailscale server.

Requirements
------------

N/A

Role Variables
--------------


Dependencies
------------



Example Playbook
----------------

```yaml
- hosts: all
  become: yes

  roles:
    - role: tailscale-install
```

License
-------

MIT

### From Ansible Galaxy

```bash
ansible-galaxy install crowjm64.tailscale_install
```

This role was created and is maintained by **[CrowJM64](https://github.com/CrowJM64)**.
