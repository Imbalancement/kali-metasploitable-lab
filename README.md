# 🔐 Kali Linux & Metasploitable Lab

> 🚀 Hands-on penetration testing lab simulating real-world attack scenarios using Kali Linux and Metasploitable2.

---

## 👨‍💻 About This Project

This is one of my first hands-on cybersecurity labs where I simulated an internal network attack.

The goal was to:
- Discover services on a target machine
- Identify vulnerabilities
- Exploit them using real tools
- Gain root-level access

---

## 🖥️ Lab Setup

| Role       | Machine           |
|------------|------------------|
| Attacker   | Kali Linux       |
| Target     | Metasploitable2  |
| Network    | Host-only        |
| Platform   | VirtualBox       |

---

## 🛠️ Tools Used

- Nmap (network scanning)
- Metasploit Framework (exploitation)
- Linux CLI
- VirtualBox

---

## 🔍 Phase 1: Reconnaissance

I scanned the target machine to identify open ports and services.

```bash
nmap -sV 192.168.56.102
