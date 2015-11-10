# Backups and Disaster Recovery

This section is dedicated to any existing means to rollback or backup your VM in Xen Orchestra.

### Full backups

You can schedule full backups of your VMs, by exporting them in the local XOA file-system, or directly in a NFS share. "Depth" parameter allow to modify the retention (removing the oldest one).

![](https://xen-orchestra.com/blog/content/images/2015/07/backupexample.png)

[Read more here](https://xen-orchestra.com/blog/backup-your-xenserver-vms-with-xen-orchestra/).

### Scheduled snapshots

This feature is close to Backups, but it creates a snapshot when planned to do so. It also handles the retention (to remove the oldest snapshot).

[Read more about it](https://xen-orchestra.com/blog/xen-orchestra-4-2/#schedulerollingsnapshots).

### Disaster recovery