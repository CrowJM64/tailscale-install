# Ansible Role for installing Tailscale
**Author/Maintainer:** Josh Murphy


## Overview
This role can either be paired with my headscale-install role, or used alone to join Ansible managed machines to a Headscale or Tailscale server.



## Requirements
------------

N/A

## Role Variables
--------------


## Supported Platforms and Derivatives
Below are the explicitly tested Distros.
```yaml
## Redhat
Rocky - 10, 9
Fedora - 44, 43
Oracle - 10, 9
AmazonLinux - 2023

## Debian
Debian - 13, 12
Ubuntu - 2604, 2404
```

## Example Playbook
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
