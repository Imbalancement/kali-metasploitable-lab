# 🔐 Kali Linux & Metasploitable Penetration Testing Lab

> 🚀 Hands-on cybersecurity lab simulating a real-world internal penetration test using Kali Linux and Metasploitable2.

---

## 👨‍💻 About This Project

This project documents a full penetration testing workflow conducted in a controlled virtual lab environment.

The objective was to:
- Discover services on a target machine
- Identify vulnerabilities
- Exploit them using real tools
- Gain root-level access
- Validate system compromise

---

## 🖥️ Lab Environment

| Role       | Machine           |
|------------|------------------|
| Attacker   | Kali Linux       |
| Target     | Metasploitable2  |
| Network    | Host-only        |
| Platform   | VirtualBox       |

---

## 🛠️ Tools Used

- Nmap (network scanning & enumeration)
- Metasploit Framework (exploitation)
- Linux CLI
- VirtualBox

---

# 🔍 Phase 1: Reconnaissance

The first step was identifying active hosts and confirming connectivity.

### Command:
```bash
ping 192.168.56.102
🔎 Phase 2: Scanning & Enumeration

I performed service and version detection using Nmap:

nmap -sV 192.168.56.102
Key Findings :

FTP → vsftpd 2.3.4 (vulnerable)

SSH → OpenSSH 4.7p1

Samba → ports 139 / 445

HTTP → Apache 2.2.8

MySQL & PostgreSQL services exposed

These results revealed multiple potential attack vectors.
