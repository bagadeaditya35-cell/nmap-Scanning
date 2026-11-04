# 🔍 Understanding Network Scanning

### Network Scanning | Nmap | Kali Linux | Metasploitable | Ethical Hacking

## 📌 Project Overview

This project demonstrates practical network scanning techniques using **Nmap, Kali Linux, and Metasploitable** in a controlled cybersecurity lab environment.

The objective is to understand how network scanning helps identify active hosts, open ports, running services, and potential security weaknesses in a network.

This practical exercise covers beginner, intermediate, and advanced network scanning concepts.

## 🎯 Project Objectives

- Understand network scanning fundamentals.
- Identify target IP addresses.
- Verify host availability.
- Discover open ports and running services.
- Perform TCP SYN scanning.
- Understand service version detection.
- Explore operating system detection.
- Identify potentially vulnerable services.
- Perform basic security risk classification.
- Recommend appropriate security measures.

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Kali Linux | Security testing environment |
| Metasploitable | Intentionally vulnerable lab machine |
| Nmap | Network scanning and enumeration |
| UFW | Firewall management |
| iptables | Network traffic filtering |

## 🖥️ Lab Environment

**Attacker Machine:** Kali Linux

**Target Machine:** Metasploitable

**Scanning Tool:** Nmap

**Environment:** Virtualized cybersecurity lab

## 🔬 Practical Implementation

### 1. Beginner-Level Practical

- Finding the IP address of Kali Linux.
- Finding the IP address of Metasploitable.
- Verifying whether the target is reachable.
- Performing basic Nmap scanning.
- Identifying open ports and services.

### 2. Intermediate-Level Practical

Explored the following scanning concepts:

- TCP SYN Scan
- Service Version Detection
- Operating System Detection
- Open Port Identification
- Service Enumeration

### 3. Advanced-Level Practical

Performed a structured network assessment covering:

1. Host Discovery
2. Full Port Scan
3. Service and Version Enumeration
4. Optional Web Scan
5. Risk Classification
6. Security Recommendations
7. Executive Summary

## 📊 Port & Service Analysis

The practical report includes the following example observations:

| Port | Service | Potential Security Risk |
|---|---|---|
| 21 | FTP | Anonymous access or insecure configuration |
| 22 | SSH | Weak authentication or misconfiguration |
| 23 | Telnet | Unencrypted communication |
| 80 | HTTP | Web application or server vulnerabilities |
| 3306 | MySQL | Weak credentials or exposed database |
| 139/445 | SMB | Vulnerable or misconfigured file-sharing services |

### Service Version Analysis

The report also documents these example observations:

| Port | Service | Version | Risk Level |
|---|---|---|---|
| 21 | FTP | vsftpd 2.3.4 | 🔴 High |
| 23 | Telnet | Not specified | 🔴 High |
| 80 | HTTP | Apache 2.2.8 | 🟡 Medium |
| 22 | SSH | OpenSSH | 🟢 Low* |

*Risk depends on configuration and software version. These are observations from the practical report, not independently verified current vulnerabilities.*

## 🚨 Security Risks Identified

The assessment highlights several potential security concerns:

- Outdated network services.
- Unencrypted communication protocols.
- Unnecessary open ports.
- Weak authentication configurations.
- Potentially vulnerable services.
- Excessive network service exposure.

## 🛡️ Security Recommendations

- Disable unnecessary ports and services.
- Replace Telnet with SSH.
- Update outdated software.
- Configure firewall rules.
- Use strong passwords and authentication.
- Restrict network access using ACLs.
- Monitor system and network logs.
- Secure or disable unnecessary FTP services.

## 📚 Key Learning Outcomes

Through this practical project, I explored:

- Network scanning fundamentals.
- Nmap scanning techniques.
- Host discovery.
- Port scanning.
- Service enumeration.
- Operating system detection concepts.
- Security risk assessment.
- Network security fundamentals.
- Vulnerability awareness.
- Defensive security practices.

## 📁 Project Structure

```text
Network-Scanning/
│
├── README.md
│
├── Documentation/
│   └── Network_Scanning_Report.pdf
│
└── Screenshots/
    ├── Lab_Setup/
    ├── Host_Discovery/
    ├── Port_Scanning/
    └── Service_Enumeration/
```

## 🎓 Project Information

**Project Name:** Understanding Network Scanning

**Domain:** Cybersecurity / Ethical Hacking

**Course:** skillected

**Author:** Aditya Kashinath Bagade

**Lab Environment:** Kali Linux & Metasploitable

## ⚠️ Disclaimer

This project is intended strictly for educational purposes and authorized cybersecurity testing.

All scanning activities should be performed only against systems owned by you or for which you have explicit authorization.

The project uses Metasploitable as an intentionally vulnerable lab environment for learning network scanning and security assessment techniques.

## 👨‍💻 Author

**Aditya Kashinath Bagade**

Cybersecurity Student | Ethical Hacking Enthusiast
