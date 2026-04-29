---
layout: default
title: Leo Mathole | Systems Administrator
---

<style>
body {
  background-color: #0d1117;
  color: #c9d1d9;
  font-family: Arial, sans-serif;
}

/* HEADINGS */
h1, h2, h3 {
  color: #00ff9c;
}

/* LINKS */
a {
  color: #00ff9c;
  text-decoration: none;
  transition: 0.3s;
}

a:hover {
  color: #00cc7a;
}

/* CONTAINER */
.container {
  max-width: 1000px;
  margin: auto;
  padding: 20px;
}

/* CARDS */
.card {
  background: #161b22;
  padding: 20px;
  margin: 25px 0;
  border-radius: 12px;
  border: 1px solid #00ff9c33;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

/* HOVER EFFECT */
.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 0 20px #00ff9c33;
}

/* IMAGES */
img {
  width: 100%;
  border-radius: 8px;
  margin-top: 10px;
  transition: transform 0.3s ease;
}

img:hover {
  transform: scale(1.02);
}

/* BADGES */
.badge {
  display: inline-block;
  padding: 6px 12px;
  margin: 5px;
  background: #00ff9c22;
  border: 1px solid #00ff9c55;
  border-radius: 6px;
  transition: 0.3s;
}

.badge:hover {
  background: #00ff9c44;
}

/* BUTTON */
.button {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 15px;
  border: 1px solid #00ff9c;
  border-radius: 6px;
  transition: 0.3s;
}

.button:hover {
  background: #00ff9c22;
}

/* FADE-IN ANIMATION */
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeIn 0.8s ease forwards;
}

.fade-in:nth-child(2) { animation-delay: 0.2s; }
.fade-in:nth-child(3) { animation-delay: 0.4s; }
.fade-in:nth-child(4) { animation-delay: 0.6s; }
.fade-in:nth-child(5) { animation-delay: 0.8s; }

@keyframes fadeIn {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>

<div class="container">

<div class="fade-in">

# Leo Mathole

### Systems Administrator | AD | Monitoring | Virtualization

</div>

<div class="card fade-in">

## Profile

I design, deploy, and troubleshoot enterprise IT systems focused on:

- Active Directory & Identity Management  
- System Monitoring (Wazuh SIEM)  
- Backup & Disaster Recovery  
- Infrastructure Reliability  

</div>

<div class="card fade-in">

## Proven Capabilities

- Built enterprise-style AD domain (DC01 + WIN11)  
- Deployed centralized SIEM monitoring  
- Implemented backup & recovery in Proxmox  
- Simulated real-world cyber incidents  
- Troubleshot system failures  

</div>

<div class="card fade-in">

## Live System Evidence

### Proxmox

![Proxmox](screenshots/proxmox/proxmox-node-overview.png)

### Wazuh

![Wazuh](screenshots/monitoring/wazuh-dashboard.png)

### Active Directory

![AD](screenshots/ad/ad-users.png)

</div>

<div class="card fade-in">

## Core Modules

<a class="button" href="ad/users-groups.md">Active Directory</a>  
<a class="button" href="ad/dns.md">DNS</a>  
<a class="button" href="monitoring/wazuh.md">Monitoring</a>  
<a class="button" href="backups/proxmox-backup.md">Backup</a>  
<a class="button" href="incidents/brute-force.md">Incident Analysis</a>  

</div>

<div class="card fade-in">

## 🛠️ Real Issues Solved

- Proxmox disk exhaustion  
- Wazuh agent failures  
- Domain authentication loop  
- Docker image pull issues  

</div>

<div class="card fade-in">

## Tech Stack

<span class="badge">Proxmox</span>
<span class="badge">Active Directory</span>
<span class="badge">Wazuh</span>
<span class="badge">Linux</span>
<span class="badge">Windows Server</span>
<span class="badge">Kali Linux</span>

</div>

<div class="card fade-in">

## 📂 Repository

<a class="button" href="https://github.com/leomathole/sysadmin-lab">View GitHub Project</a>

</div>

<div class="card fade-in">

## 📞 Contact

- Email: leomathole@gmail.com  
- Phone: +265 888 881 406  

</div>

</div>
