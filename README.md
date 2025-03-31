# Semaphore Updater for Debian

The goal of this project is to provide an easy way to update semaphore installed via .deb package.
Tested on Debian 12.

# Usage
Grab the ansible playbook and the upgrade script locally, then program it with cron:

```
0 12 * * * /usr/bin/ansible-playbook /etc/ansible/playbooks/update-semaphore.yml
```
