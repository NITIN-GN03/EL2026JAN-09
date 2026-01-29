# EL2026JAN-09
This project demonstrates Network Vulnerability Scanning using Nmap. It covers local network discovery, open port identification, service and OS detection, vulnerability analysis, and risk assessment. The task focuses on ethical scanning, interpreting results, and documenting findings to strengthen network reconnaissance and security awareness.
# Task 9: Network Vulnerability Scanning

## 📌 Overview
This project focuses on performing Network Vulnerability Scanning using **Nmap** to identify security weaknesses in a local network. The task demonstrates core concepts of network reconnaissance, including port scanning, service enumeration, OS detection, and vulnerability analysis.

> ⚠️ All scans were performed on authorized networks for educational purposes only.

---

## 🛠 Tools Used
- **Nmap**
- **Masscan** (alternative)

---

## 🎯 Objectives
- Scan a local network
- Identify live hosts
- Detect open ports
- Enumerate running services
- Identify operating systems
- Analyze potential vulnerabilities
- Interpret security risks
- Document findings

---

## 🔍 Scanning Methodology

### 1. Discover Live Hosts
```bash
nmap -sn 192.168.1.0/24
