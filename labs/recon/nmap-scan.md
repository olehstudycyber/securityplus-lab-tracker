# 🔍 Recon Lab: Nmap Scan

## 🧪 Objective
Perform active network reconnaissance using Nmap to identify live hosts, open ports, and services.

## 🧰 Tools Used
- Kali Linux
- Nmap (`nmap`, `nmap -sS`, `nmap -A`, etc.)

## 🧠 Methodology
1. Scan the subnet: `nmap -sn 192.168.1.0/24`
2. Identify open ports on the target: `nmap -sV 192.168.1.2`
3. Aggressive scan for full details: `nmap -A 192.168.1.2`

## 📋 Results
- Host discovered: `192.168.1.2` (Windows Server 2025)
- Open ports: 80 (HTTP), 135 (RPC), 445 (SMB), 3389 (RDP)
- Services: Microsoft IIS, SMBv3

## 📎 Screenshots / Logs
> _Add terminal screenshots and scan outputs here._

## 🔐 Security+ Objectives Covered
- 3.3: Given a scenario, research threats, vulnerabilities, and exploits
- 4.3: Use appropriate tools to assess organizational security
