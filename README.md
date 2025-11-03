# Task-1-Scan-Your-Local-Network-for-Open-Port
A basic Nmap task to scan the local network and identify devices with open ports.

# Quick Scan Result

Port 53/tcp open — dnsmasq 2.84rc2 (Medium risk) on 192.168.64.128/24

---

## What I ran (short)
Commands I used on my local Kali machine:
```bash
ip a
sudo nmap -sS -sV 192.168.64.128/24

