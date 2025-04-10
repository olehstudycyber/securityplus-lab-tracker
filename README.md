 🧠 Cybersecurity Lab Tracker – Oleh Borysovskyy

## ✅ Overview
This file tracks my progress through hands-on cybersecurity projects in my home lab, aligned with the CompTIA Security+ exam objectives and real-world penetration testing scenarios.

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
- 🔗 [`reports/`](./reports/)

---

## 🔚 Notes

This tracker will be updated regularly as I advance through projects, attacks, defense, and study objectives. It's part of my portfolio toward landing a cybersecurity analyst role.
