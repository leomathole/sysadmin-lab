# Backup and Recovery Strategy

## Objective

To ensure system availability and data recovery in case of failure.

## Method

Using Proxmox built-in backup functionality.

## Configuration Steps

1. Navigate to Datacenter → Backup
2. Create a backup job
3. Select VMs:
   - DC01
   - WIN11
4. Set schedule (Daily/30 minutes)

## Backup Mode

- Snapshot mode used for consistency

## Testing Recovery

### Scenario

- Deleted a test user from Active Directory

### Action

- Restored VM from backup

## Evidence

### Backup Job

![](![](../sysadmin-lab/screenshots/backups/backup-job.png))

### Backup Success

![](![](../sysadmin-lab/screenshots/backups/backup-success.png))

### Restore Process

![](![](../sysadmin-lab/screenshots/backups/backing-restore.png))
=======

![](![](../sysadmin-lab/screenshots/backups/backup-job.png))

### Backup Success

![](![](../sysadmin-lab/screenshots/backups/backup-success.png))

### Restore Process

![](![](../sysadmin-lab/screenshots/backups/backing-restore.png))

## Result

- System successfully restored
- Data integrity maintained

## Importance

Backups ensure:

- Business continuity
- Disaster recovery readiness

## Conclusion

Backup and restore procedures are functional and reliable.
