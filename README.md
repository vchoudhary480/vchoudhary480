# Hi 👋, I'm Vishwa Prakash Choudhary

**Computer Science @ UC Davis** · **IT intern @ Nokia** . Aspiring **SOC Analyst** · Cybersecurity concentration

[![Portfolio](https://img.shields.io/badge/Portfolio-2563eb?style=flat-square)](https://vchoudhary480.github.io/vishwa-portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vishwa-prakash-choudhary-541036291/)
---

## 📌 About Me

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="200" align="right"/>

I'm a Computer Science student at UC Davis focused on cybersecurity, threat detection, network traffic analysis, and security architecture. I'm currently pursuing **CompTIA Security+**, and building hands-on projects that show I can actually do the work, not just talk about it.

- 🎯 Targeting entry-level **SOC Analyst** and security engineering roles
- 🔍 Currently focused on threat detection, SIEM tooling, and vulnerability assessment
- 🛠️ Building practical projects in network analysis and cloud security
- 📜 Studying for **CompTIA Security+ (SY0-701)**
- 🎓 Graduating **August 2026**

<br clear="right"/>

---

## 🛠️ Tech & Tools

**Languages & Scripting:**
Python, Bash, SQL (basics)

**Security & Networking:**
Wireshark, Splunk, Metasploit, Nmap

**Cloud & Platforms:**
AWS (IAM, S3, CloudTrail, GuardDuty), Linux (Kali, Ubuntu), VirtualBox / VMware

**Concepts:**
Log Analysis, Incident Response, MITRE ATT&CK, NIST Frameworks, Cryptography Fundamentals, TCP/IP & Networking

---

## 🔐 Featured Projects

### [🔒 SIEM Home Lab — Attack Detection & Analysis](https://github.com/vchoudhary480/siem-home-lab)

Built a fully isolated VirtualBox lab simulating real-world cyberattacks against an intentionally vulnerable Metasploitable 3 target, with Splunk Enterprise ingesting logs via rsyslog over UDP. Ran three attack scenarios end-to-end and verified that every attack was detected and logged.

Conducted network reconnaissance using Nmap and discovered 9 exposed services including FTP, SSH, HTTP, and MySQL. Executed an SSH brute force attack with Hydra that generated 1,961 security events at over 200 events per minute, all captured in Splunk. Exploited the ProFTPD 1.3.5 mod_copy vulnerability via Metasploit to obtain a reverse shell with full remote code execution, with the entire attack chain visualized in a Splunk dashboard. Achieved a 100% detection rate across all 3 simulated attack scenarios with zero missed events.

**Stack:** Splunk Enterprise, Kali Linux, Metasploitable 3, Metasploit, Nmap, Hydra, VirtualBox, rsyslog

---

### [🦈 Wireshark Network Traffic Analysis](https://github.com/vchoudhary480/Wireshark-Network-Analysis)

Analyzed real network traffic to expose how insecure protocols silently leak credentials and session data. Captured and dissected Telnet sessions to reconstruct full keystroke-by-keystroke command history, then captured live traffic from a home network and found that DNS queries expose every visited domain to anyone on the same Wi-Fi, even when HTTPS protects the actual page content.

Built a Python + Scapy automation tool that accepts any `.pcap` file and flags plaintext credentials, insecure protocols, DNS leaks, and insecure ports, with every finding mapped to a MITRE ATT&CK technique ID. Recovered a complete cleartext login session including username, password, and post-auth command history from a single packet capture. Compiled a professional findings report documenting severity ratings, protocol behavior, and recommended mitigations relevant to SOC and threat hunting workflows.

**Stack:** Python, Scapy, Wireshark

---

### [☁️ AWS Cloud Security Hardening](https://github.com/vchoudhary480/aws-security-hardening)

Hardened a live AWS account against common cloud misconfigurations and built a suite of Python (Boto3) audit scripts to detect them automatically. Configured IAM with user/group separation, root account lockdown, and MFA enforcement across all privileged accounts. Secured S3 with AES-256 encryption, bucket versioning, and account-level public access blocking, and enabled multi-region CloudTrail logging with AWS Config for continuous compliance monitoring.

Developed 4 audit scripts covering IAM, S3, and security groups across all enabled AWS regions, producing machine-readable JSON reports suitable for SIEM ingestion or CI/CD pipeline gates. Mapped every check to a CIS AWS Foundations Benchmark v1.4 control. Validated detection accuracy by deliberately introducing misconfigurations, including edge cases like large CIDR blocks and wildcard S3 policies hidden behind condition blocks and confirmed 100% detection with zero false positives across 3 simulated attack scenarios.

**Stack:** Python, Boto3, AWS (IAM, S3, CloudTrail, AWS Config, Security Groups)

---

## 📜 Certifications

**In Progress**
- CompTIA Security+ (SY0-701)

**Completed**
- [Foundations of Cybersecurity — Google](https://www.coursera.org/learn/foundations-of-cybersecurity) *(Coursera)*
- [Play It Safe: Manage Security Risks — Google](https://www.coursera.org/learn/manage-security-risks) *(Coursera)*
- AIG Shields Up: Cybersecurity Job Simulation

---

## 📫 How to Reach Me

- 💼 LinkedIn: [vishwa-prakash-choudhary](https://www.linkedin.com/in/vishwa-prakash-choudhary-541036291/)
- 🌐 Portfolio: [vchoudhary480.github.io/vishwa-portfolio](https://vchoudhary480.github.io/vishwa-portfolio)
- 🔵 Email: choudharyvishwaprakash480@gmail.com
