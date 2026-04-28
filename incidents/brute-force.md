# Incident: Brute Force Attack Detection

## Objective

Simulate and detect unauthorized login attempts.

## Attack Method

Performed multiple failed login attempts on Windows 11.

## Tools Used

- Windows Multiple login
- Windows Event Viewer
- Wazuh SIEM

## Evidence

### Attack Source

![](![attack%20source](../screenshots/incidents/attack-kali.png))

### Windows Logs

![](![windows%20logs](../screenshots/incidents/failed-login.png))

### Wazuh Detection

![](![wazuh%20detection](../screenshots/incidents/wazuh-detection.png))

## Analysis

- Multiple failed login attempts detected
- Correlated timestamps between systems
- Alert triggered in Wazuh

## Conclusion

Demonstrates ability to:

- Detect suspicious activity
- Analyze logs
- Respond to incidents
