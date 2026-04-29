# Lab Architecture

## Overview

This lab simulates an enterprise IT infrastructure using virtualization and multiple operating systems.

## Infrastructure

### Proxmox VE

- Acts as the hypervisor
- Hosts all virtual machines

### Virtual Machines

#### DC01 (Windows Server)

- Active Directory Domain Controller
- DNS Server

#### WIN11

- Domain-joined client
- Used for user simulation

#### OPS (Ubuntu Server)

- Wazuh SIEM
- Zeek network monitoring

#### KALI

- Attack simulation and testing

## Architecture Diagram

![](../screenshots/proxmox/proxmox-node-overview.png)

## Communication Flow

```
WIN11 → DC01 (Authentication)
WIN11 → OPS (Logs to Wazuh)
KALI → WIN11 (Attack simulation)
OPS → Analysis (Wazuh Dashboard)
```

## Design Considerations

- Isolated lab environment
- Realistic enterprise simulation
- Resource-efficient deployment

## Conclusion

The architecture supports system administration, monitoring, and incident simulation effectively.
