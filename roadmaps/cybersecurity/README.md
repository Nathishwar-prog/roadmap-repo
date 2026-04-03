# 🔐 Cybersecurity Roadmap

> **Goal:** Understand how attackers think, learn to defend systems, and build skills for a career in information security — from networking fundamentals to penetration testing and incident response.

---

## 📌 Overview

| Stage | Topics | Estimated Time |
|---|---|---|
| 🟢 Beginner | Networking, OS, Security concepts, Linux | 6–8 weeks |
| 🟡 Intermediate | Web security, Crypto, Ethical hacking basics | 8–12 weeks |
| 🔴 Advanced | Penetration testing, Malware analysis, Blue team, Cloud security | 12–16 weeks |

> ⚠️ **Ethics First:** Only apply offensive security techniques on systems you own or have explicit written permission to test. Unauthorized hacking is illegal.

---

## 🟢 Stage 1 — Beginner

**Goal:** Build the foundational knowledge every security professional needs.

### 🌐 Networking Fundamentals
- ✅ OSI model and TCP/IP stack (all 7 layers)
- ✅ IP addressing, subnetting, CIDR notation
- ✅ DNS — how domain resolution works
- ✅ HTTP vs HTTPS, TLS/SSL handshake
- ✅ Common protocols: FTP, SSH, SMTP, DHCP, ARP
- ✅ Firewalls, NAT, and proxies (conceptual)
- ✅ Wireshark — capture and analyze network traffic

### 🐧 Operating Systems
- ✅ **Linux** essentials: file system, permissions, processes, users
- ✅ Bash scripting basics
- ✅ **Windows** internals: registry, Active Directory concepts, PowerShell basics
- ✅ Virtualization: set up a VirtualBox / VMware lab

### 🔑 Security Fundamentals
- ✅ CIA Triad: Confidentiality, Integrity, Availability
- ✅ Authentication vs Authorization
- ✅ Common threats: phishing, malware, ransomware, social engineering
- ✅ Security policies, risk management, compliance (GDPR, HIPAA concepts)
- ✅ Types of hackers: white hat, black hat, grey hat
- ✅ Bug bounty programs and responsible disclosure

### 🔐 Cryptography Basics
- ✅ Symmetric vs asymmetric encryption
- ✅ Common algorithms: AES, RSA, SHA-256
- ✅ Hashing and salting passwords
- ✅ Public Key Infrastructure (PKI)
- ✅ TLS certificates and HTTPS

### 🛠️ Beginner Projects:
- 🌐 Set up a home lab with VirtualBox and Kali Linux
- 🔍 Capture and analyze traffic with Wireshark on a local network
- 🔑 Write a Python script that hashes passwords with salt using `hashlib`
- 📋 Document a threat model for a simple web application

---

## 🟡 Stage 2 — Intermediate

**Goal:** Learn offensive and defensive security techniques for web apps and networks.

### 🌐 Web Application Security (OWASP Top 10)
- ✅ **Injection attacks**: SQL injection, Command injection, XSS
- ✅ **Broken authentication** and session management
- ✅ **IDOR** — Insecure Direct Object References
- ✅ **CSRF** — Cross-Site Request Forgery
- ✅ **Security misconfigurations** and exposed sensitive data
- ✅ **SSRF** — Server-Side Request Forgery
- ✅ **XXE** — XML External Entity injection
- ✅ Using Burp Suite to intercept and manipulate web requests

### 🔍 Network Security
- ✅ Port scanning with **Nmap**
- ✅ Vulnerability scanning with **Nessus** or **OpenVAS**
- ✅ Network sniffing and MitM concepts
- ✅ VPNs, proxies, and anonymization
- ✅ Intrusion Detection Systems (IDS) and SIEM concepts

### 🐚 Ethical Hacking Basics
- ✅ Reconnaissance: passive (OSINT) vs active information gathering
- ✅ OSINT tools: Shodan, Google Dorking, `theHarvester`, `Maltego`
- ✅ Exploitation basics with **Metasploit**
- ✅ Password attacks: brute force, dictionary attacks, `Hydra`, `Hashcat`
- ✅ Privilege escalation (Linux & Windows concepts)

### 🛡️ Blue Team / Defense
- ✅ Log analysis with Splunk or ELK Stack
- ✅ Incident response lifecycle (Preparation → Identification → Containment → Eradication → Recovery)
- ✅ Threat hunting fundamentals
- ✅ Hardening systems (CIS benchmarks)

### 🛠️ Intermediate Projects:
- 🎯 Complete 10+ rooms on [TryHackMe](https://tryhackme.com/) covering web and network attacks
- 🕷️ Find and exploit a SQL injection on a deliberately vulnerable app (DVWA)
- 🔍 Write a Python port scanner using `socket`
- 🛡️ Set up a SIEM with the ELK stack and ingest sample logs

---

## 🔴 Stage 3 — Advanced

**Goal:** Develop specialist skills in penetration testing, cloud security, or malware analysis.

### 🎯 Penetration Testing
- ✅ Penetration testing methodology: scoping, recon, exploitation, reporting
- ✅ Web app pentesting with Burp Suite Pro
- ✅ Active Directory attacks: Kerberoasting, Pass-the-Hash, BloodHound
- ✅ Internal network pivoting and tunneling
- ✅ Writing pentest reports with clear findings and remediation steps
- ✅ Bug bounty hunting on HackerOne / Bugcrowd

### 🧬 Malware Analysis & Reverse Engineering
- ✅ Static analysis: file headers, strings, PE structure
- ✅ Dynamic analysis: running malware in sandboxes
- ✅ Tools: **Ghidra**, **IDA Pro**, **Cuckoo Sandbox**
- ✅ Assembly language basics (x86/x64)
- ✅ YARA rules for malware detection

### ☁️ Cloud Security
- ✅ AWS IAM misconfigurations and privilege escalation
- ✅ S3 bucket misconfiguration attacks
- ✅ Container and Kubernetes security
- ✅ Cloud security tools: **Prowler**, **Scout Suite**, **Pacu**
- ✅ Cloud security frameworks: CSA CCM, AWS Well-Architected

### 🔒 Advanced Defense (Blue Team)
- ✅ Threat intelligence (MITRE ATT&CK framework)
- ✅ Digital forensics: disk imaging, memory forensics, timeline analysis
- ✅ SOC operations and alert triage
- ✅ Red team vs Blue team exercises
- ✅ Writing detection rules (Sigma, Yara, Suricata)

### 🛠️ Advanced Projects:
- 🎯 Obtain a root/admin flag on a HackTheBox machine
- 🔬 Analyze a malware sample in a safe sandbox environment and write a report
- ☁️ Audit an AWS environment for misconfigurations with Prowler
- 🏆 Participate in a live CTF (Capture the Flag) competition

---

## ⏱️ Estimated Time

| Stage | Duration |
|---|---|
| Beginner | 6–8 weeks (1–2 hrs/day) |
| Intermediate | 8–12 weeks (2 hrs/day) |
| Advanced | 12–16 weeks (2–3 hrs/day) |
| **Total** | **~9–12 months** |

---

## 📚 Resources

### Free Learning Platforms:
- 🔗 [TryHackMe](https://tryhackme.com/) — Beginner-friendly, guided hacking rooms
- 🔗 [HackTheBox](https://www.hackthebox.com/) — Realistic penetration testing labs
- 🔗 [OWASP WebGoat](https://owasp.org/www-project-webgoat/) — Deliberately insecure web app to practice on
- 🔗 [DVWA](https://github.com/digininja/DVWA) — Damn Vulnerable Web App (self-hosted lab)
- 🔗 [PicoCTF](https://picoctf.org/) — CTF challenges designed for beginners
- 🔗 [Cybrary](https://www.cybrary.it/) — Free cybersecurity courses

### Books:
- 📖 *The Web Application Hacker's Handbook* — Stuttard & Pinto (web security bible)
- 📖 *Penetration Testing* — Georgia Weidman (hands-on, beginner-friendly)
- 📖 *Hacking: The Art of Exploitation* — Jon Erickson (low-level details)
- 📖 *The Hacker Playbook 3* — Peter Kim (practical pentest scenarios)
- 📖 *Blue Team Handbook* — Don Murdoch (defensive security reference)

### Practice:
- 🏋️ [PortSwigger Web Security Academy](https://portswigger.net/web-security) — Free, world-class web security labs
- 🏋️ [HackTheBox Academy](https://academy.hackthebox.com/) — Structured cybersecurity curriculum
- 🏋️ [VulnHub](https://www.vulnhub.com/) — Free downloadable vulnerable VMs

---

## 🏅 Certifications to Aim For

| Certification | Provider | Level |
|---|---|---|
| CompTIA Security+ | CompTIA | 🟢 Beginner |
| eJPT (Junior Penetration Tester) | eLearnSecurity | 🟢 Beginner |
| CEH (Certified Ethical Hacker) | EC-Council | 🟡 Intermediate |
| OSCP (Offensive Security Certified Professional) | Offensive Security | 🔴 Advanced |
| CISSP | (ISC)² | 🔴 Advanced |

---

## 🔮 What's Next?

- ☁️ Secure your cloud infrastructure: [DevOps Roadmap](../devops/README.md)
- 🏗️ Understand systems to protect: [System Design Roadmap](../system-design/README.md)
- 🌐 Secure your web apps: [Web Development Roadmap](../web-development/README.md)

---

[⬅️ Back to Main README](../../README.md)
