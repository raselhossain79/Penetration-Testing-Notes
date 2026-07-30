# 🔐 Penetration Testing Notes

A comprehensive collection of industry-level penetration testing and vulnerability assessment notes covering Network, Web Application, and API security testing methodologies.

> **Disclaimer:** These notes are for **authorized penetration testing and educational purposes only**. Unauthorized use of these techniques against systems you do not own or have explicit written permission to test is illegal.

---

## 📁 Repository Structure

```
Penetration-Testing-Notes/
├── 01_Network_Pentest/
│   ├── 01_External_Network_Pentest_Windows.md
│   ├── 02_External_Network_Pentest_Linux.md
│   ├── 03_Internal_Network_Pentest_Windows.md
│   ├── 04_Internal_Network_Pentest_Linux.md
│   ├── 05_External_VA_Windows.md
│   ├── 06_External_VA_Linux.md
│   ├── 07_Internal_VA_Windows.md
│   └── 08_Internal_VA_Linux.md
├── 02_Web_Application_Pentest/
│   ├── 01_Web_App_Pentest_Full.md
│   └── 02_Web_App_VA.md
└── 03_API_Pentest/
    ├── 01_API_Pentest_Full.md
    └── 02_API_VA.md
```

---

## 📖 What's Inside

### 🌐 01 — Network Penetration Testing

| File | Type | Scope |
|---|---|---|
| External Network Pentest — Windows | Full Pentest | RDP, SMB, WinRM, IIS, Exchange, MSSQL, AD |
| External Network Pentest — Linux | Full Pentest | SSH, FTP, Apache, Redis, MongoDB, Docker, Samba |
| Internal Network Pentest — Windows | Full Pentest | Active Directory, Kerberoasting, NTLM Relay, DCSync |
| Internal Network Pentest — Linux | Full Pentest | Internal services, Privilege Escalation, Pivoting |
| External VA — Windows | VA | Safe identification of Windows external vulnerabilities |
| External VA — Linux | VA | Safe identification of Linux external vulnerabilities |
| Internal VA — Windows | VA | AD misconfiguration checks, BloodHound analysis |
| Internal VA — Linux | VA | Internal service misconfigs, CIS benchmark checks |

### 🌍 02 — Web Application Penetration Testing

| File | Type | Scope |
|---|---|---|
| Web App Pentest — Full | Full Pentest | SQLi, XSS, IDOR, SSRF, SSTI, XXE, JWT, CSRF, Business Logic |
| Web App VA | VA | Safe identification across OWASP Top 10 |

### 🔌 03 — API Penetration Testing

| File | Type | Scope |
|---|---|---|
| API Pentest — Full | Full Pentest | BOLA, Auth, Injection, Rate Limiting, GraphQL, SOAP |
| API VA | VA | OWASP API Top 10 safe identification and coverage |

---

## 🧭 Methodology Standards

All notes follow industry-recognized standards:

- **PTES** — Penetration Testing Execution Standard
- **OWASP Testing Guide v4.2** — Web Application Security Testing
- **OWASP API Security Top 10 (2023)** — API Security
- **NIST SP 800-115** — Technical Guide to Information Security Testing
- **CVSSv3** — Common Vulnerability Scoring System

---

## 🔄 Pentest vs Vulnerability Assessment

Each topic has **two separate notes** — understanding the difference is critical:

| | Penetration Test | Vulnerability Assessment |
|---|---|---|
| Goal | Exploit vulnerabilities — prove real-world impact | Identify and list vulnerabilities safely |
| Exploitation | ✅ Yes | ❌ No |
| Risk to client | Moderate (controlled) | Very Low |
| Output | Attack chain + proof of compromise | Prioritized vulnerability list + remediations |
| Analogy | Stress test | Health checkup |

---

## 🛠️ Core Tools Referenced

| Category | Tools |
|---|---|
| Scanning | nmap, Nessus, OpenVAS, Nuclei, Nikto |
| Web/API | Burp Suite, OWASP ZAP, sqlmap, ffuf, gobuster |
| AD / Windows | BloodHound, CrackMapExec, Impacket, Mimikatz, Responder |
| Linux | LinPEAS, Lynis, LinEnum, Chisel |
| Recon | subfinder, amass, theHarvester, Shodan |
| Crypto | hashcat, John the Ripper, testssl.sh |

---

## 📋 Each Note Contains

✅ Concept explanation (what and why)  
✅ Phase-by-phase methodology  
✅ Real commands with explanations  
✅ OS/platform-specific techniques  
✅ CVE reference tables  
✅ Common misconfigurations checklist  
✅ Reporting guidance (CVSS scoring, finding templates)  
✅ Remediation recommendations  
✅ Full methodology checklist  

---

## ⚖️ Legal & Ethical Use

- Always obtain **written authorization** before testing any system
- Never test systems you do not own or have explicit permission to test
- Follow your engagement's **Rules of Engagement (RoE)** at all times
- All techniques in these notes are for **authorized engagements only**

---

## 👤 Author

**MD Rasel Hossain**  
Junior Penetration Tester  
📍 Dhaka, Bangladesh

[![GitHub](https://img.shields.io/badge/GitHub-raselhossain79-181717?style=flat&logo=github)](https://github.com/raselhossain79)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rasel--hossain-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/rasel-hossain-73b954395)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-theloser-212C42?style=flat&logo=tryhackme)](https://tryhackme.com/p/theloser)

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


