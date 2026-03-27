# 🛡️ Cybersecurity Portfolio — Rey

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Freelance-red?style=for-the-badge&logo=hackthebox&logoColor=white)
![OSINT](https://img.shields.io/badge/OSINT-Investigations-blue?style=for-the-badge&logo=tor-project&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Bash-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Phishing](https://img.shields.io/badge/Phishing-Detection-orange?style=for-the-badge&logo=virustotal&logoColor=white)

> **A hands-on cybersecurity portfolio covering OSINT investigations, vulnerability assessments, phishing detection, Linux security scripting, and log analysis — built through real-world freelance engagements and independent research.**

---

## 📌 About This Portfolio

This repository documents my practical cybersecurity work as a **freelance security analyst**, covering multiple domains of defensive and investigative security. Each section contains real tools, scripts, reports, and methodologies used in actual engagements.

**Focus Areas:**
- 🔍 OSINT & Digital Investigations
- 🦟 Phishing Detection & Analysis
- 🖥️ Linux Security & Bash Automation
- 🔎 Vulnerability Assessment
- 📊 Log Analysis & Threat Hunting

---

## 📁 Repository Structure

```
cyber_security_portfolio/
│
├── OSINT-Investigations/         # Open-source intelligence research & tools
├── Vulnerability-Assessment/     # Security scanning, reports & findings
├── Linux-Bash-projects/          # Security automation scripts (Bash/Python)
└── Interview-prep/               # Security concepts, notes & writeups
```

---

## 🔍 OSINT Investigations

**Open Source Intelligence** research using publicly available data sources to gather, analyze, and correlate threat intelligence.

### Skills Demonstrated:
- Passive reconnaissance techniques
- Digital footprint analysis
- Social engineering awareness & detection
- Threat actor profiling
- Tools: `theHarvester`, `Maltego`, `Shodan`, `WHOIS`, `Recon-ng`

### Use Cases:
```
✔ Domain & IP reputation investigation
✔ Email address and identity verification
✔ Social media intelligence gathering
✔ Infrastructure mapping of targets
```

---

## 🦟 Phishing Detection & Analysis

Practical work identifying, analyzing, and reporting phishing campaigns — completed as part of **cybersecurity freelance engagements**.

### Methodology:
```
1. URL & Domain Analysis
        ↓
2. Email Header Inspection
        ↓
3. Payload / Attachment Analysis
        ↓
4. IOC Extraction (IPs, Domains, Hashes)
        ↓
5. Threat Report Generation
```

### Tools & Techniques:
- URL scanning: `VirusTotal`, `URLScan.io`, `PhishTank`
- Header analysis: `MXToolbox`, manual inspection
- Sandbox detonation for attachment analysis
- Python scripts for automated URL classification

---

## 🖥️ Linux Bash Projects

Security-focused Bash and Python scripts for **log analysis, system hardening, and threat detection automation**.

### Projects Include:

| Script | Purpose |
|---|---|
| Log Parser | Extract suspicious patterns from system/auth logs |
| Failed Login Monitor | Detect brute-force attempts via SSH |
| File Integrity Checker | Alert on unauthorized file modifications |
| Network Port Scanner | Internal network enumeration |
| Phishing URL Classifier | Python ML-based URL threat scoring |

### Sample — Log Analysis Snippet:
```bash
# Extract failed SSH login attempts with IP addresses
grep "Failed password" /var/log/auth.log | \
  awk '{print $11}' | \
  sort | uniq -c | \
  sort -rn | head -20
```

---

## 🔎 Vulnerability Assessment

Structured vulnerability identification and reporting using industry-standard methodologies.

### Assessment Workflow:
```
Scope Definition
      ↓
Reconnaissance & Enumeration
      ↓
Vulnerability Scanning (Nmap, Nikto, OpenVAS)
      ↓
Manual Verification
      ↓
Risk Rating (CVSS Scoring)
      ↓
Remediation Report
```

### Tools Used:
- `Nmap` — Network scanning & service enumeration
- `Nikto` — Web server vulnerability scanning
- `OpenVAS` / `Nessus` — Automated vulnerability assessment
- `Burp Suite` — Web application testing
- `Metasploit` — Exploitation framework (lab environments only)

---

## 📊 Log Analysis & Threat Hunting

Analyzing system, network, and application logs to identify **indicators of compromise (IOCs)** and anomalous behavior.

### Log Sources Analyzed:
- Linux `auth.log` / `syslog`
- Apache / Nginx web server access logs
- Firewall and network flow logs
- Windows Event Logs (Security, System)

### Threat Patterns Detected:
```
✔ Brute-force login attempts
✔ Privilege escalation indicators
✔ Lateral movement signatures
✔ Data exfiltration patterns
✔ Malware C2 beacon traffic
```

---

## 🎯 Interview Prep

Security concepts, writeups, and study notes covering:

- **CompTIA Security+** core domains
- **SOC Analyst** interview questions & answers
- **Incident Response** playbooks
- **Network security** fundamentals
- **CTF writeups** and challenge solutions

---

## 🛠️ Tools & Technologies

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kali-linux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-Security-blue?style=flat-square)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![VirusTotal](https://img.shields.io/badge/VirusTotal-394EFF?style=flat-square)

---

## ⚠️ Ethical Disclaimer

> All security work documented in this portfolio was performed **ethically and legally** — either on personal lab environments, deliberately vulnerable machines (e.g. HackTheBox, TryHackMe), or with **explicit written client authorization** for freelance engagements.
>
> No unauthorized systems were accessed. This portfolio is shared strictly for **educational and professional demonstration purposes**.

---

## 👩‍💻 Author

**Rey** — Cybersecurity Analyst | DevOps Engineer | OSINT Researcher
- GitHub: [@rey26341-sudo](https://github.com/rey26341-sudo)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> *Built through real freelance cybersecurity engagements, self-directed research, and continuous learning — combining technical depth with practical, real-world application.*
