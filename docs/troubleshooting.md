---

---

# Troubleshooting Log

## Objective

Document real issues encountered and solutions applied.

---

## Issue 1: Wazuh Agent Not Connecting

### Problem

Agent not appearing in manager.

### Cause

Incorrect configuration and firewall restrictions.

### Solution

- Verified manager IP
- Opened required ports
- Restarted wazuh-agent service

---

## Issue 2: Windows Domain Login Loop

### Problem

User forced to change password repeatedly.

### Cause

Password policy mismatch.

### Solution

- Reset password from DC01
- Disabled “must change at next login”

---

## Issue 3: Docker Image Pull Failures

### Problem

Images failing to download.

### Cause

Disk space exhaustion.

### Solution

- Cleaned Docker system
- Freed up disk space

---

## Issue 4: Proxmox Storage Full

### Problem

VMs failing due to no disk space.

### Cause

Local-LVM reached 100%.

### Solution

- Removed unused images
- Cleaned storage

---

## Result

- All issues resolved successfully
- System stability restored
- Improved troubleshooting skills
