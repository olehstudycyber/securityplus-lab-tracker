# 🕵️ Detection Lab: Sysmon + Windows Event Analysis

## 🧪 Objective
Use Sysmon logs to detect suspicious activity and investigate attacker behavior.

## 🧰 Tools Used
- Windows Event Viewer
- Sysmon (configured with SwiftOnSecurity config)
- Windows Defender

## 🧠 Methodology
1. Trigger known suspicious behavior (e.g., Meterpreter session, lateral movement).
2. Analyze `Sysmon` logs: look for process creation, network connections, etc.
3. Document Indicators of Compromise (IOCs) and map attacker behavior.

## 📋 Results
- Detected abnormal process: `cmd.exe` spawning `powershell.exe`
- Suspicious outbound connection to Kali IP: `192.168.1.10`
- Event ID 1, 3, and 10 helped track activity

## 📎 Screenshots / Logs
> _Add relevant Sysmon logs, event IDs, and timelines._

## 🔐 Security+ Objectives Covered
- 4.1: Analyze indicators of malicious activity
- 4.2: Summarize the importance of security monitoring
