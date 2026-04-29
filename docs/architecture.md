

# System Architecture

## Objective

Design a structured enterprise-like lab environment simulating real-world infrastructure.

## Overview

The lab environment consists of four main systems:

- **DC01** – Domain Controller (Active Directory + DNS)
- **WIN11** – Domain-joined client machine
- **OPS** – Monitoring server (Wazuh SIEM)
- **KALI** – Attack simulation machine

## Architecture Design

![Architecture](../screenshots/docs/architecture.png)

## Components

### 1. Domain Controller (DC01)

- Active Directory Domain Services
- DNS Server
- User authentication

### 2. Client Machine (WIN11)

- Joined to domain
- Used for testing authentication and policies

### 3. Monitoring Server (OPS)

- Wazuh SIEM deployed
- Collects logs from endpoints

### 4. Attacker Machine (KALI)

- Used for brute-force simulation
- Security testing

## Result

A fully functional enterprise-style lab environment enabling:

- Identity management
- Monitoring
- Security testing
- Troubleshooting scenarios
