# Ansible Demo Project
---
An Ansible learning project to try out managing different kinds of hosts with local configurations and inventories.

#### Hosts
* `localhost`: running MacOS

Initially there is also the `playgrounds` group that points to sandbox Linux servers.

* `centos`: points to a personal Python 3.7 CentOS dev server named `python-server`
* `ubuntu`: points to a generic Ubuntu 18.04 server `ubuntu-server` not cofigured for anything specific.

#### Users
On the local MacOS setup, asnible will connect locally and use my username which has `sudo` rights.

On the playgrounds, there is a pre-configured `ansible` user which has been added to `sudoers` with the `NOPASSWD` option.