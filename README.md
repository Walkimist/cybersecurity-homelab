# Cybersecurity Homelab

## Objective

This is a project to document my cybersecurity journey while setting up my first homelab! Here I will be writing down the milestones and difficulties I face during the construction of the lab.

You can view more details about the different OS's being used and their configuration processes under the notes folder.

### I'll be using it to hone my skills on:
- Linux
- Networking
- SSH
- Virtualization
- Cybersecurity fundamentals

---

## Environment

```text
                Windows Host
                      │
              Oracle VirtualBox
                      │
               192.168.56.0/24
        ┌─────────────┴─────────────┐
        │                           │
        │                           │
  Ubuntu Server                 Kali Linux
  192.168.56.101                   nmap
       SSH
```
---
## VM Uses

### Ubuntu Server:
- Linux administration practice
- SSH remote management
- Service deployment and configuration
- Firewall and system hardening
- Network security testing

### Kali Linux:
- Network enumeration
- Nmap scanning
- Linux practice
- Cybersecurity labs
---

## VM Configurations

### Ubuntu Server
| Resource | Amount |
|---|---|
| RAM | 2048 MB |
| CPU | 1 vCPU |
| Disk | 20 GB |

### Kali Linux

| Resource | Amount |
|---|---|
| RAM | 4096 MB |
| CPU | 2 vCPU |
| Disk | 30 GB |
---

## To-do

- Install Apache on Ubuntu
- Learn Nmap scripting (NSE).
- Configure firewall
