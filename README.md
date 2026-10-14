# Homelab ELK Stack Configuration

Repository containing custom configuration files for my Homelab SIEM environment based on the ELK Stack (Elasticsearch, Logstash, Kibana).

## Architecture
- **Hypervisor:** VirtualBox / VMware
- **Log Sources:** Windows Server (Event Logs via Winlogbeat), Ubuntu Server (Syslog, Nginx logs).
- **Goal:** Centralize logs for identifying suspicious activities and practicing Threat Hunting.
