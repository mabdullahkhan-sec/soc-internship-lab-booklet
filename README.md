# SOC Internship Lab Booklet

A compiled documentation booklet covering all SOC lab work completed during my internship at **ITSOLERA** (Jan 2026 – Apr 2026). Each lab section covers tool deployment, configuration, real-world use cases, and key findings structured as a professional reference for SOC operations.

---

## Overview

| Detail | Info |
|---|---|
| Organization | ITSOLERA (Remote) |
| Role | SOC Analyst Intern |
| Duration | January 2026 – April 2026 |
| Format | Compiled Lab Booklet (PDF) |

---

## Tools & Labs Covered

### 🛡️ Wazuh SIEM
- Deployed Wazuh for centralized log collection and security event monitoring
- Configured File Integrity Monitoring (FIM) for real-time alerting on unauthorized file changes
- Tuned alert rules for threat detection and incident triage

### 🔥 pfSense Firewall
- Integrated pfSense with Wazuh SIEM for centralized network traffic visibility
- Configured firewall rules, traffic filtering, and logging pipelines

### 🦠 ClamAV + Squid Proxy
- Deployed ClamAV antivirus alongside Squid Proxy on pfSense
- Configured malware download blocking with Wazuh alerting integration

### 🔬 REMnux - Malware Analysis
- Used REMnux toolkit for static and dynamic malware analysis
- Mapped malware behaviors and indicators to the MITRE ATT&CK framework

### 🔍 Ghidra - Reverse Engineering
- Used Ghidra for binary reverse engineering and disassembly
- Extracted indicators of compromise (IOCs) from malware samples

### ⚙️ n8n - SOC Automation
- Built automated SOC alert triage workflows using n8n
- Configured real-time classification, notifications, and escalation pipelines

---

## Key Concepts Demonstrated

- SIEM deployment and rule tuning
- File Integrity Monitoring (FIM)
- Network traffic monitoring and firewall integration
- Malware analysis and MITRE ATT&CK mapping
- SOC workflow automation
- Incident detection and alert triage

---

## Files

| File | Description |
|---|---|
| `SOC_Lab_Booklet.pdf` | Full compiled lab booklet |

---

## Frameworks Referenced

- MITRE ATT&CK
- NIST Incident Response Lifecycle

---

*Completed as part of SOC Analyst Internship at ITSOLERA · 2026*
