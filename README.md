# Cybersecurity Homelab

## Objective

This is a project to document my cybersecurity journey while setting up my first homelab! Here I will be writing down the milestones and difficulties I face during the construction of the lab.  

### I'll be using it to hone my skills on:
- Linux
- Networking
- SSH
- Virtualization
- Cybersecurity fundamentals

---

## Environment

- Windows 11 Host
- VirtualBox
- Ubuntu Server 24.04

---

## VM Configuration

| Resource | Amount |
|---|---|
| RAM | 2048 MB |
| CPU | 1 vCPU |
| Disk | 20 GB |

---

## Network Configuration

- Adapter 1: NAT
- Adapter 2: Host-Only Adapter

---

## SSH Configuration

Installed OpenSSH Server:

```bash
sudo apt install openssh-server -y
```

Learned how to check service status:

```bash
systemctl status ssh
```

Connected from Windows cmd:

```powershell
ssh labadmin@192.168.56.101
```

---

## Troubleshooting

I Had an issue where SSH connection was timing out when trying to connect from the Windows cmd.
To fix it, I Learned how to configure Host-Only Adapter in VirtualBox.

---

## Screenshots

### SSH Running
![SSH Running](screenshots/ssh-running.png)

### Network Adapter
![Network Adapter 1](screenshots/network-adapter-1.png)
![Network Adapter 2](screenshots/network-adapter-2.png)

### IP Config
![IP Config](screenshots/ip-config.png)

### Windows cmd Connected
![Windows cmd Connected](screenshots/windows-cmd-connected.png)

---

## To-do

- Install Kali Linux
- Learn Nmap
- Configure firewall
- Build internal lab network
