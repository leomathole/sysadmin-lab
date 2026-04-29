# Backup and Recovery Strategy

## Objective

To ensure system availability and enable full data recovery in case of system failure, corruption, or security incidents.

---

## Method

Backups are implemented using the built-in backup functionality in Proxmox VE.

---

## Configuration Steps

1. Navigate to **Datacenter → Backup**
2. Click **Add** to create a new backup job
3. Select the virtual machines:
   - DC01 (Domain Controller)
   - WIN11 (Client Machine)
4. Configure backup schedule:
   - Daily or every 30 minutes (lab testing scenario)
5. Select storage location (local or external storage)
6. Choose backup mode (Snapshot)

---

## Backup Mode

- **Snapshot mode** is used to ensure consistency without shutting down virtual machines.

---

## Testing Recovery

### Scenario

- A test user was deleted from Active Directory to simulate data loss.

### Action

- The affected VM (DC01) was restored from a previous backup.

---

## Evidence

### Backup Job

![Backup Job](../screenshots/backups/backup-job.png)

### Backup Success

![Backup Success](../screenshots/backups/backup-success.png)

### Restore Process

![Restore Process](../screenshots/backups/backing-restore.png)

---

## Result

- System successfully restored
- Deleted Active Directory objects recovered
- Data integrity maintained

---

## Importance

Backups ensure:

- Business continuity
- Disaster recovery readiness
- Protection against data loss
- Rapid system restoration

---

## Conclusion

The backup and recovery process has been successfully configured and tested.  
The system can be reliably restored in the event of failure, meeting enterprise system administration requirements.
