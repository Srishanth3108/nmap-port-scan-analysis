# Task 1: Nmap Port Scanning - Cyber Security Internship

## 🎯 Objective
Perform network reconnaissance by identifying open ports on devices in a local network using Nmap.

## 🧰 Tools Used
- Kali Linux (VirtualBox VM)
- Nmap

## 🌐 Network Info
- **eth0** → Subnet: `10.0.2.0/24`
- **eth1** → Subnet: `172.30.1.0/24`

## 📟 Commands Used
```bash
sudo nmap -sS 10.0.2.0/24 -oN scan_eth0.txt
sudo nmap -sS 172.30.1.0/24 -oN scan_eth1.txt
