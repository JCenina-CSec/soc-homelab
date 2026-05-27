# SOC Homelab

## Overview
Built a virtualized cybersecurity homelab using Proxmox VE to simulate enterprise-style infrastructure and SOC workflows.

---

## Technologies Used
- Proxmox VE
- Ubuntu Server
- Kali Linux
- Windows 11 Pro
- Docker
- Pi-hole
- Portainer
- Uptime Kuma
- Wireshark
- Nmap

---

## Skills Practiced
- Network analysis
- Linux hardening
- DNS monitoring
- Vulnerability investigation
- Service monitoring
- Incident documentation
- Virtualization
- Infrastructure troubleshooting

---

## Lab Architecture
### Proxmox Infrastructure

![Proxmox Dashboard](images/proxmox-dashboard.png)

The homelab environment is hosted on Proxmox VE and includes Ubuntu Server, Kali Linux, and Windows virtual machines used for infrastructure management, security monitoring, network analysis, and SOC-style investigation workflows.

## Pi-hole DNS Monitoring

![Pi-hole Dashboard](images/Pi-Hole-dashboard.png)

Implemented Pi-hole for DNS filtering, visibility, and network telemetry monitoring within the homelab environment. Used to analyse DNS activity, blocked queries, client behaviour, and upstream resolver activity.

## Service Monitoring with Uptime Kuma

![Uptime Kuma Dashboard](images/Up-time-kuma-dashboard.png)

Configured Uptime Kuma to monitor the availability and health of self-hosted infrastructure and Docker services. Used to track outages, service interruptions, response failures, and uptime statistics across the homelab environment.

## Docker Container Management

![Portainer Dashboard](images/portainer-dashboard.png)

Used Portainer to manage Docker containers, stacks, networks, and self-hosted services within the homelab environment. Implemented containerized infrastructure for monitoring, DNS filtering, dashboards, and security testing applications.

---

## Security Activities
- Nmap reconnaissance
- Wireshark packet analysis
- DNS visibility investigation
- SSH hardening
- UFW firewall configuration
- Fail2ban deployment

---

## Future Improvements
- Wazuh SIEM
- Active Directory
- Sysmon logging
- Security Onion
- Splunk
- Centralized logging
- SOC alert simulation
