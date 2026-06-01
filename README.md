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
        ┌─────────────┴─────────────┐
        │                           │
        │                           │
  Ubuntu Server                 Kali Linux
  192.168.56.101              
       SSH
```
---

## VM Configurations

### Ubuntu Server
| Resource | Amount |
|---|---|
| RAM | 2048 MB |
| CPU | 1 vCPU |
| Disk | 20 GB |

### Kali Attacker

| Resource | Amount |
|---|---|
| RAM | 4096 MB |
| CPU | 2 vCPU |
| Disk | 30 GB |

## To-do

- Install Kali Linux
- Learn Nmap
- Configure firewall
- Build internal lab network
