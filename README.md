# dovecot-backup-swift
**This is a fork from [tachtler/dovecot-backup](https://github.com/tachtler/dovecot-backup). Thanks for your cool work!**

## Features
You can find all features, issues etc. on the repository of the original project: [tachtler/dovecot-backup](https://github.com/tachtler/dovecot-backup)

### What I've added
I missed some things, that's why I've added these features:
- Uploading the created archive file to OpenStack Swift Object Storage
- Sending a Discord webhook about the status of the backup

## Prerequisites
You need to have the [openstack-swiftclient](https://github.com/openstack/python-swiftclient) installed and the correct [environment variables](https://docs.openstack.org/python-swiftclient/latest/cli/index.html#authentication) set, so that `swift list` does correctly show your containers.