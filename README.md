# 🔐 Kali Linux & Metasploitable Penetration Testing Lab

> Hands-on cybersecurity lab simulating real-world penetration testing using Kali Linux, Metasploitable2, and VirtualBox.

---

## 🧠 Overview

This project demonstrates a full penetration testing workflow in a controlled virtual lab environment.  

I built a lab using Kali Linux (attacker) and Metasploitable2 (target), then performed reconnaissance, vulnerability analysis, exploitation, and post-exploitation.

---

## 🖥️ Lab Environment

- **Attacker:** Kali Linux  
- **Target:** Metasploitable2  
- **Platform:** VirtualBox  
- **Network:** Host-only adapter  

---

## 🛠️ Tools Used

- Nmap  
- Metasploit Framework  
- Linux CLI  
- VirtualBox  

---

## 🔍 Reconnaissance (Nmap Scan)

I performed service and version detection using:

```bash
nmap -sV 192.168.56.102
