---
layout: default
title: "Backup & Recovery Strategy"
permalink: /backups/proxmox/
---

# 💾 Backup & Recovery Strategy

## Objective

Ensure system availability and disaster recovery capability.

---

## Configuration

- Platform: Proxmox VE
- Mode: Snapshot
- Schedule: Daily

---

## Steps

1. Navigate to Datacenter → Backup
2. Create backup job
3. Select VMs:
   - DC01
   - WIN11
4. Set schedule

---

## Evidence

### 📦 Backup Job

![Backup Job](screenshots/backups/backup-job.png)

### ✅ Backup Success

![Backup Success](screenshots/backups/backup-success.png)

### 🔄 Restore Process

![Restore](screenshots/backups/backing-restore.png)

---

## Result

- Successful restore completed
- No data loss observed

---

## Importance

- Disaster recovery readiness
- Business continuity assurance

---
