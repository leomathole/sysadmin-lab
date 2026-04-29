# 🖥️ Systems Administration Portfolio

## 👤 Leo Mathole

**Aspiring Systems Administrator | Virtualization | Monitoring | Active Directory**

---

## 🚀 Project Overview

This portfolio demonstrates hands-on implementation of enterprise systems administration tasks, including identity management, system monitoring, backup strategies, and incident analysis.

The environment was built using virtualization and simulates a real-world enterprise infrastructure.

---

## 🧰 Technologies Used

- Proxmox VE (Virtualization)
- Windows Server (Active Directory, DNS)
- Windows 11 (Client)
- Ubuntu Server (Monitoring)
- Wazuh SIEM (Security Monitoring)
- Linux CLI Tools

---

## 🏗️ Lab Architecture

![Proxmox Overview](screenshots/proxmox/proxmox-node-overview.png)

- **DC01** → Domain Controller + DNS  
- **WIN11** → Domain-joined client  
- **OPS** → Monitoring server (Wazuh)  
- **KALI** → Attack simulation  

---

## 🔐 Core Implementations

### 🧑‍💼 Active Directory & User Management

- Created users, groups, and Organizational Units  
- Enforced authentication policies  
- Managed role-based access control  

👉 [View Implementation](ad/users-groups.md)

---

### 🌐 DNS Configuration

- Configured internal domain (`lab.local`)  
- Enabled name resolution across systems  

👉 [View DNS Setup](ad/dns.md)

---

### 📊 System Monitoring (Wazuh)

- Centralized log monitoring  
- Detected failed login attempts  
- Analyzed system activity  

![Wazuh Dashboard](screenshots/monitoring/wazuh-dashboard.png)

👉 [View Monitoring Setup](monitoring/wazuh.md)

---

### 💾 Backup & Recovery

- Configured scheduled backups in Proxmox  
- Tested restore scenarios  
- Ensured data integrity  

![Backup Job](screenshots/backups/backup-job.png)

👉 [View Backup Strategy](backups/proxmox-backup.md)

---

### ⚠️ Incident Simulation

- Simulated brute-force attack  
- Captured logs and alerts  
- Performed analysis  

![Attack Simulation](screenshots/incidents/attack-kali.png)

👉 [View Incident Analysis](incidents/brute-force.md)

---

## 🛠️ Troubleshooting Experience

During this project, I encountered and resolved real-world issues:

- Disk storage exhaustion on Proxmox  
- Wazuh agent connectivity issues  
- Windows domain authentication errors  
- Docker deployment failures  

👉 [View Troubleshooting Log](docs/troubleshooting.md)

---

## 🎯 Key Skills Demonstrated

- Systems Administration  
- Active Directory Management  
- DNS Configuration  
- System Monitoring & Logging  
- Backup & Disaster Recovery  
- Troubleshooting & Incident Handling  

---

## 📂 Project Repository

👉 https://github.com/leomathole/sysadmin-lab

---

## 📞 Contact

- Email: leomathole@gmail.com
- Phone: 0888881406 

---

## 📌 Note

This project was built as a practical demonstration of enterprise system administration skills aligned with real-world IT environments.
