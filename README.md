# 🛡️ Ethical Hacking & Vulnerability Management Lab

This repository provides a complete lab guide and structure for ethical hacking and vulnerability management using VirtualBox, Kali Linux, Metasploit, Nessus, and Burp Suite. It simulates a real-world penetration testing workflow from reconnaissance to reporting.

---

## 🚀 Lab Objectives

- Set up a vulnerable test network
- Perform reconnaissance and scanning using Nmap and Nessus
- Exploit services with Metasploit
- Test web applications with Burp Suite
- Map vulnerabilities to CVEs, CVSS scores, and MITRE ATT&CK techniques
- Author a professional penetration testing report

---

## 🧰 Tools Used

- **Kali Linux** – Offensive Security Distro
- **Metasploitable2** – Deliberately vulnerable Linux target
- **Metasploit Framework** – Exploitation tool
- **Nessus Essentials** – Free vulnerability scanner
- **Burp Suite Community Edition** – Web app testing tool
- **VirtualBox** – Virtualization platform

---

## 🔧 Lab Setup

### 1. Download and Configure VMs

| VM | RAM | Network | Link |
|----|-----|---------|------|
| Kali Linux | 4 GB | NAT + Host-Only | [kali.org/get-kali](https://www.kali.org/get-kali/) |
| Metasploitable2 | 1 GB | Host-Only | [sourceforge.net](https://sourceforge.net/projects/metasploitable/) |

Ensure all VMs are connected to a common `vboxnet0` (Host-Only Adapter).

---

