 🧠 Cybersecurity Lab Tracker – Oleh Borysovskyy

## ✅ Overview
This file tracks my progress through hands-on cybersecurity projects in my home lab, aligned with the CompTIA Security+ exam objectives and real-world penetration testing scenarios.
## 🖼️ Lab Network Diagram

![Lab Network Diagram](./reports/lab_network_diagram.png)## 🖼️ Lab Network Diagram

![Lab Network Diagram](./reports/lab_network_diagram.png)
---

## 📅 Activity Log

| Date       | Task/Experiment                                      | Tools Used              | Notes |
|------------|-------------------------------------------------------|--------------------------|-------|
| 2025-04-10 | Scanned Windows Server 2025 w/ Nmap                   | Nmap                     | Found open ports: 22, 80, 445 |
| 2025-04-11 | Enum4linux scan on target                             | Enum4linux              | Pulled domain info via SMB |
| 2025-04-12 | Created tracker + updated README.md                   | Markdown                | Polished repo presentation |

---

## 🔍 Recon & Scanning Progress

- [x] Nmap scanning
- [x] Netdiscover
- [x] Enum4linux
- [ ] Nikto
- [ ] Dirb / Gobuster

---

## 💥 Exploitation Techniques Practiced

| Technique              | Target              | Status     | Notes |
|------------------------|---------------------|------------|-------|
| SMB Exploitation       | Windows Server 2025 | ✅ Complete | SMBv1 confirmed; tested exploits |
| SSH Brute Force        | Windows Server 2025 | 🔄 In Progress | Hydra attempts; account lockout triggered |

---

## 🛡 Hardening & Monitoring Progress

- [x] Installed Sysmon on Server
- [x] Enabled Windows Defender rules
- [ ] Setup Wazuh Manager (Coming soon)
- [ ] Configure log forwarding to Wazuh
- [ ] Write Sigma detection rules

---

## 📖 Security+ Study Tracker

| Domain                         | % Complete | Notes |
|--------------------------------|------------|-------|
| 1.0 Threats, Attacks, & Vulns | 80%        | Reviewing port/protocol questions |
| 2.0 Architecture & Design      | 60%        | Diagrams & secure configs |
| 3.0 Implementation             | 70%        | Practicing tools in lab |
| 4.0 Operations & Incident Resp | 40%        | Will start blue team exercises |
| 5.0 Governance & Risk          | 50%        | Notes from HRCI cert helping here |

---

## 📂 Key Repo Links

- 🔗 [`recon_logs/`](./recon_logs/)
- 🔗 [`exploitation/`](./exploitation/)
- 🔗 [`post_exploitation/`](./post_exploitation/)
- 🔗 [`SIEM_IDS/`](./SIEM_IDS/)


# 🛡️ 30-Day CompTIA Security+ (701) Lab-Integrated Study Plan

## 📆 Week 1: Core Security Concepts + Basic Attacks
**🧠 Focus Areas:**
- CIA triad, threat actors, frameworks
- Malware, social engineering, risk concepts
- Network attacks and terminology
**🧪 Lab Tasks:**
- Simulate phishing with Kali (SET)
- Capture Nmap and traffic with Wireshark
- Document attack types in tracker

### Day 1 (Saturday, April 12):
- [ ] Study topics from **Week 1**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 2 (Sunday, April 13):
- [ ] Study topics from **Week 1**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 3 (Monday, April 14):
- [ ] Study topics from **Week 1**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 4 (Tuesday, April 15):
- [ ] Study topics from **Week 1**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 5 (Wednesday, April 16):
- [ ] Study topics from **Week 1**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 6 (Thursday, April 17):
- [ ] Study topics from **Week 1**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 7 (Friday, April 18):
- [ ] Study topics from **Week 1**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

## 📆 Week 2: Network Security + Secure Design
**🧠 Focus Areas:**
- Secure protocols (HTTPS, SSH, SFTP)
- Network segmentation, firewall, proxies
- Monitoring and hardening basics
**🧪 Lab Tasks:**
- Analyze traffic with Wireshark
- Set up SSH and secure router
- Configure iptables/UFW and scan ports

### Day 8 (Saturday, April 19):
- [ ] Study topics from **Week 2**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 9 (Sunday, April 20):
- [ ] Study topics from **Week 2**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 10 (Monday, April 21):
- [ ] Study topics from **Week 2**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 11 (Tuesday, April 22):
- [ ] Study topics from **Week 2**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 12 (Wednesday, April 23):
- [ ] Study topics from **Week 2**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 13 (Thursday, April 24):
- [ ] Study topics from **Week 2**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 14 (Friday, April 25):
- [ ] Study topics from **Week 2**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

## 📆 Week 3: Identity, Access, and SIEM
**🧠 Focus Areas:**
- MFA, RBAC, tokens, account policies
- Active Directory, Kerberos, LDAP
- SIEM (Wazuh), logging, Sysmon
**🧪 Lab Tasks:**
- Set up AD users and roles
- Deploy Wazuh and explore logs
- Harden access control policies

### Day 15 (Saturday, April 26):
- [ ] Study topics from **Week 3**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 16 (Sunday, April 27):
- [ ] Study topics from **Week 3**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 17 (Monday, April 28):
- [ ] Study topics from **Week 3**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 18 (Tuesday, April 29):
- [ ] Study topics from **Week 3**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 19 (Wednesday, April 30):
- [ ] Study topics from **Week 3**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 20 (Thursday, May 01):
- [ ] Study topics from **Week 3**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 21 (Friday, May 02):
- [ ] Study topics from **Week 3**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

## 📆 Week 4: Hardening + Review + Practice Exams
**🧠 Focus Areas:**
- System updates, patching, services
- Incident response, BCP, DRP
- Practice exams and review
**🧪 Lab Tasks:**
- Harden Windows & Linux OS
- Simulate and analyze mock incidents
- Final walkthrough of all systems

### Day 22 (Saturday, May 03):
- [ ] Study topics from **Week 4**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 23 (Sunday, May 04):
- [ ] Study topics from **Week 4**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 24 (Monday, May 05):
- [ ] Study topics from **Week 4**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 25 (Tuesday, May 06):
- [ ] Study topics from **Week 4**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 26 (Wednesday, May 07):
- [ ] Study topics from **Week 4**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 27 (Thursday, May 08):
- [ ] Study topics from **Week 4**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

### Day 28 (Friday, May 09):
- [ ] Study topics from **Week 4**
- [ ] Complete at least one lab task
- Take notes in `SECURITYPLUS_LAB_TRACKER.md`

---

💡 **Tip:** Aim for 85–90% on practice tests before booking your exam.


- 🔗 [`reports/`](./reports/)

---

## 🔚 Notes

This tracker will be updated regularly as I advance through projects, attacks, defense, and study objectives. It's part of my portfolio toward landing a cybersecurity analyst role.
