# usenet-srv

Rebuildable home usenet server utilizing containers.

Note: Ansible assumes the host server OS is Fedora.

## Pre-Ansible Setup

1. `ssh-copy-id` to server

2. passwordless `sudo` on server

3. create an ansible hosts file

```ini
[usenet]
<ip address>
```
