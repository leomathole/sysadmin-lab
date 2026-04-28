# Monitoring with Wazuh

## Objective

To implement centralized log monitoring and detect suspicious activities.

## Server Details

- Host: OPS (Ubuntu Server)
- IP Address: 192.168.10.30

## Installation Method

- Installed Wazuh using official installation script
- Deployed:
  - Wazuh Manager
  - Wazuh Dashboard

## Agent Configuration

### Windows 11

- Installed Wazuh agent
- Registered using authentication key
- Connected to manager

## Verification

### Agent Status

```
sudo /var/ossec/bin/agent_control -l
```

## Evidence

### Dashboard

![](file:///D:/sysadmin-lab/screenshots/monitoring/wazuh-dashboard.png)

### Alerts

![](file:///D:/sysadmin-lab/screenshots/monitoring/wazuh-alerts.png)

## Use Cases

- Failed login detection
- Monitoring system activity
- Log correlation

## Challenges

### Issue: Agent not connecting

- Cause: Not registered
- Fix: Used `manage_agents` to generate key

### Issue: Docker failures (initial attempt)

- Fix: Switched to native installation

## Conclusion

Wazuh successfully provides centralized monitoring and supports security analysis.
