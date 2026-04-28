# Troubleshooting Log

## 1. Proxmox Storage Full

### Issue

- local-lvm reached 100%

### Cause

- Docker images consumed disk space

### Fix

- Cleaned Docker images
- Expanded LVM storage

---

## 2. Wazuh Agent Not Connecting

### Issue

- Agent not listed

### Cause

- Agent not registered

### Fix

- Used `manage_agents`
- Imported authentication key

---

## 3. Windows Login Loop

### Issue

- User forced to change password repeatedly

### Cause

- Domain communication issue

### Fix

- Verified DNS and domain connectivity

---

## 4. Docker Failures

### Issue

- Images failing to pull

### Cause

- Network instability and disk issues

### Fix

- Switched to native installation

---

## Conclusion

Multiple real-world issues were identified and resolved, demonstrating strong troubleshooting skills.
