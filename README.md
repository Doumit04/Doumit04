# Hi, I'm Tony Doumit 👋

**Cybersecurity Engineer** · Beirut, Lebanon  
CS Graduate · Started MSc in Cybersecurity (USJ) — Aug 2026 · Top 5.1% on TryHackMe · Building security tools from scratch

![Fortinet FCA](https://img.shields.io/badge/Fortinet-FCA-blueviolet) ![Fortinet NSE3](https://img.shields.io/badge/Fortinet-NSE3-blue) ![Fortinet NSE2](https://img.shields.io/badge/Fortinet-NSE2-0d6efd) ![Fortinet NSE1](https://img.shields.io/badge/Fortinet-NSE1-0d6efd) ![Fortinet FCF](https://img.shields.io/badge/Fortinet-FCF-6610f2) ![Cisco Endpoint Security](https://img.shields.io/badge/Cisco-Endpoint%20Security-049fd9) ![Cisco Intro to Cybersecurity](https://img.shields.io/badge/Cisco-Intro%20to%20Cybersecurity-049fd9)

---

## 🔍 About Me

I'm a computer science graduate focused on **defensive security** — threat detection, log analysis, SIEM architecture, and penetration testing. I don't just study security concepts; I build the tools that implement them.

My projects mirror real enterprise security workflows: from a full SIEM pipeline mapped to MITRE ATT&CK, to a hybrid phishing detection engine, to a two-phase penetration test with 18 custom detection rules, to a hybrid-encrypted log transport pipeline, to custom runtime-detection rules on a live Linux host with Falco.

- 🛡️ Focused on: **SOC Analysis · Threat Detection · Detection Engineering**
- 🔧 Open to: internship opportunities and entry-level security roles in Lebanon
- 💼 LinkedIn: [linkedin.com/in/tony-doumit](https://linkedin.com/in/tony-doumit)
- 🧠 TryHackMe: [tryhackme.com/p/tonydoumit15](https://tryhackme.com/p/tonydoumit15)

---

## 🚀 Featured Projects

### 🟠 [Falco Runtime Security — Custom Detection Rules for a Linux Host](https://github.com/Doumit04/falco-runtime-security)
> Falco · eBPF · Ubuntu 24.04 · YAML rules · Bash · MITRE ATT&CK

Wrote **9 custom Falco rules** that detect a planted setuid backdoor, network scanners, attack tools, and tampering with Falco itself, mapped to MITRE ATT&CK (T1548.001, T1046, T1562.001). Tested every rule with a deliberate trigger on a live Ubuntu VM and measured its noise in normal use. **Tuned three rules** with narrow exceptions: one default rule went from **27 false alerts to 0** while a real `cat /etc/shadow` still raised the alert. Includes an 11-scene live demo script and a 73-page report.

---

### 🟢 [NetWatchman — Network Intrusion Detection System](https://github.com/Doumit04/netwatchman)
> Python · Flask · MITRE ATT&CK · Scapy · REST APIs

Python-based modular NIDS with 16 independent attack detectors spanning reconnaissance, credential theft, denial-of-service, web exploitation, and data exfiltration. Every alert mapped to a MITRE ATT&CK technique across 9 tactics. Includes a real-time Flask dashboard with live replay mode and PDF/CSV export.

---

### 🔵 [LogSentry — SIEM Log Analyzer & Threat Detection Engine](https://github.com/Doumit04/LogSentry)
> Python · MITRE ATT&CK · STIX 2.0 · AbuseIPDB API · Jinja2

Built a multi-source threat detection engine mirroring enterprise SIEM architecture (Splunk, IBM QRadar). Deployed a **4-layer pipeline** (Parser → Detector → Correlator → Reporter) across 10 modules with detectors for brute force, insider threat, credential stuffing, and web attacks. Cross-source correlator links multi-stage kill chains into a single attack narrative. Mapped to **8 MITRE ATT&CK techniques** via STIX 2.0. Backed by a 41-page technical document.

---

### 🟡 [PhishGuard — Phishing Email Analyzer](https://github.com/Doumit04/PhishGuard)
> Python · Flask · VirusTotal API v3 · Regex · Unicode Normalisation

Hybrid phishing detection engine combining an **11-rule heuristic scoring system** with live VirusTotal threat intelligence (70+ security engines). Targets 6 attack vectors including domain typosquatting, Reply-To header forgery, and brand impersonation. Achieved **100% correct classification** with zero false positives across all test cases. Backed by a 19-page technical report.

---

### 🔴 [Penetration Testing & Network Traffic Analysis Lab](https://github.com/Doumit04/Metasploitable-2---pentest)
> Kali Linux · Metasploit · Wireshark · Nmap · Snort/Suricata · VirtualBox

Two-phase security assessment on Metasploitable 2. Phase 1: full TCP recon across 30 open ports, exploited 7 vulnerabilities across 6 attack categories, achieved **root access (uid=0)** on 4 of 7 exploits — compiled into a 122-page report. Phase 2: re-executed all exploits with Wireshark capture, wrote **18 Snort/Suricata detection rules**, documented IOCs from the SOC analyst perspective.

---

### 🟣 [SecureLogShipper — Encrypted Log Transport Tool](https://github.com/Doumit04/SecureLogShipper)
> C# · .NET 10 · AES-256 + RSA-2048 · TCP Sockets

Secure log transport tool using hybrid AES+RSA encryption to protect SIEM/NIDS log data (e.g., NetWatchman alerts) while in transit. Implements per-message AES key generation for forward secrecy, RSA-2048 key exchange, and a full sender/receiver TCP pipeline — mirroring the core cryptographic approach used by TLS.

---

## 🛠️ Technical Skills

**Security Tools**  
`Falco` `Wireshark` `Nmap` `Metasploit` `Snort/Suricata` `Burp Suite` `Netcat` `msfvenom` `Tcpdump`

**Security Domains**  
`Threat Detection` `Runtime Security` `SIEM Architecture` `Log Analysis` `Penetration Testing` `Detection Engineering` `Incident Response` `Email Security` `Vulnerability Assessment`

**Frameworks**  
`MITRE ATT&CK` `STIX 2.0`

**Development**  
`Python` `JavaScript` `PHP` `C++` `C#` `SQL` `React` `REST APIs`

**Platforms & Tools**  
`Linux CLI` `Bash` `eBPF` `VirtualBox` `Git/GitHub` `MySQL` `PostgreSQL`

---

## 📜 Certifications

- ✅ [**Fortinet Certified Associate (FCA) in Cybersecurity**](https://www.credly.com/earner/earned/badge/8d00316c-9e00-4958-97b0-877954c19486) — Fortinet | Issued Jun 27, 2026 · Valid until Jun 27, 2028
- ✅ [**NSE 3 – Cybersecurity**](https://www.credly.com/earner/earned/badge/18b44dbf-f3f4-4057-b5c8-7eafeb6fc8b3) — Fortinet | Issued Jun 27, 2026 · Valid until Jun 27, 2028
- ✅ **NSE 2 – Cybersecurity** — Fortinet | Issued Jun 10, 2026 · Valid until Jun 27, 2028
- ✅ [**NSE 1 – Cybersecurity**](https://www.credly.com/earner/earned/badge/ab034d06-2f2e-4efe-85af-7fdfc6e519db) — Fortinet | Issued Jun 10, 2026 · Valid until Jun 27, 2028
- ✅ [**Fortinet Certified Fundamentals (FCF) in Cybersecurity**](https://www.credly.com/earner/earned/badge/44b048da-ee79-462f-a39d-8b2e44cfcdcb) — Fortinet | Issued Jun 10, 2026 · Valid until Jun 27, 2028
- 🏆 [**TryHackMe Cybersecurity Foundations**](https://tryhackme.com/p/tonydoumit15) — Bronze League Winner, 1st Place (Top 5.1%)
- ✅ [**Cisco — Endpoint Security**](https://www.credly.com/earner/earned/badge/5e30011d-715b-4bb9-a710-c191cb7350ea) — Cisco | Issued Dec 5, 2025 (Score: 91%)
- ✅ [**Cisco — Introduction to Cybersecurity**](https://www.credly.com/earner/earned/badge/d135bf42-a3b2-4cb6-80a0-58c810acb36c) — Cisco | Issued Nov 24, 2025 (Score: 80%)

---

*"Most security students use pre-built tools. I build the tools — because understanding the internals is what makes a great defender."*
