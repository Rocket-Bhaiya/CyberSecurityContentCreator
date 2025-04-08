

## 🎯 Course Title:

**“Practical Ethical Hacking Course (Hindi)”**

---

## 🧩 **Module 1: Introduction & Setup**

**Goal:** Tools, environment & mindset ready karna

- Introduction to Ethical Hacking & Life Cycle
- Virtual Lab Setup (VirtualBox/VMware + Kali Linux + Windows + DVWA/Metasploitable)
- Networking Basics for Hackers
- Linux Basics & Command Line Crash Course
- Legal Boundaries & Hacking Ethics

🧪 *Mini Task:* Setup lab, scan local network

---

## 🔍 **Module 2: Reconnaissance (Information Gathering)**

**Goal:** Target ki sari info nikaalna bina detect hue

### Passive Recon:

- Google Dorking
- WHOIS, DNSdumpster, Subdomain Enumeration
- Social Media Footprinting & Employee OSINT

### Active Recon:

- Ping Sweep, Traceroute, DNS Enumeration
- Banner Grabbing, Network Mapping

**Tools:**\
`theHarvester`, `Recon-ng`, `Shodan`, `Maltego`, `Spiderfoot`

🧪 *Hands-On:* Targeted recon on a demo site (e.g., dvwa.local)

---

## 📡 **Module 3: Scanning (Vulnerability Discovery)**

**Goal:** Weak points dhoondhna, ports aur services identify karna

- Network Scanning: TCP, SYN, UDP
- Port Scanning: Nmap Deep Dive
- Service Fingerprinting
- Vulnerability Scanning

**Tools:**\
`Nmap`, `Nessus`, `OpenVAS`, `Nikto`, `Masscan`, `WhatWeb`

🧪 *Hands-On:* Perform detailed scan on Metasploitable2 & analyze vulnerabilities

---

## 🛠️ **Module 4: Gaining Access (Exploitation)**

**Goal:** Exploit karke system me ghusna

- Exploitation Basics (CVEs, payloads, shells)
- Exploiting Web Apps (SQLi, XSS, RCE)
- Brute Force Attacks (Hydra, Medusa)
- System Exploitation (Metasploit use)

**Tools:**\
`Metasploit`, `Burp Suite`, `SQLmap`, `Hydra`, `Searchsploit`

🧪 *Hands-On:* Exploit vulnerable login + upload shell + gain reverse shell

---

## 🔄 **Module 5: Maintaining Access**

**Goal:** Andar ghuske wapas aane ka rasta banana

- Creating Backdoors (Reverse Shell, Webshell, Bind Shell)
- Using Netcat & Meterpreter Persistence
- Privilege Escalation Techniques (Linux/Windows)
- Scheduled Jobs, Startup Scripts, Registry Manipulation

**Tools:**\
`Netcat`, `Msfvenom`, `Empire`, `Crontab`, `WinPEAS`, `LinPEAS`

🧪 *Hands-On:* Setup persistent backdoor in Windows via Metasploit

---

## 🧹 **Module 6: Covering Tracks**

**Goal:** Saboot mitaana aur trace-proof banna

- Log File Locations (Linux + Windows)
- Log Manipulation & Deletion
- Using Timestomp, Meterpreter Cleanup
- Anti-forensics basics

**Tools:**\
`Timestomp`, `clearev`, `LogCleaner`, manual deletion

🧪 *Hands-On:* Access logs, modify timestamps, clear footprints

---

## 🧾 **Module 7: Reporting & Remediation**

**Goal:** Real-world report dena jaise client ko milta hai

- Professional Vulnerability Reporting (Templates)
- How to Write PoC (Proof of Concept)
- Risk Rating (CVSS) & Recommendation Writing
- Reporting Tools (Dradis, Faraday, Markdown)

🧪 *Project:* Make a full report of your attack chain with screenshots + fix suggestions

