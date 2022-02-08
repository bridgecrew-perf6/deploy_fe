# FireEye Deployment

## FireEye Installation for RHEL/Debian based hosts

The playbook will first check for an existing installation by searching for `/opt/fireeye/bin/xagt`. The installation will then run depending on the `OS Family` that Ansible detects. Currently only `Red Hat` and `Debian` systems are supported.

### To Do List:
- Add task for MacOS
- Possibly add RPM/Debian packages to remote storage
