# devtowntask
projectCTF
# 🛡️ Penetration Testing Report

## 📌 Project Title
**Multi-Phase Penetration Testing on Target VMs**

## 🧑 Author
Sajad Hussain    
📅 Date: June 3, 2025

---

## 📘 Overview

This project demonstrates practical penetration testing skills on two separate vulnerable virtual machines:

1. **Basic Pentesting 1 VM**
2. **ProFTPD 1.3.3c Backdoor VM**

The goal was to perform full-cycle reconnaissance, exploitation, post-exploitation, and password cracking.

---

## 📂 Files Included

- `Penetration_Testing_Final_Report.pdf` – Full detailed report (with ToC, page numbers, screenshots references, tools used, and results)
- `hashes.txt` – Extracted password hash from `/etc/shadow`
- `README.md` – This documentation file

---

## 🧪 Tools Used

| Tool           | Purpose                              |
|----------------|--------------------------------------|
| `nmap`         | Port scanning and service detection  |
| `nikto`        | Web server vulnerability enumeration |
| `enum4linux`   | SMB enumeration                      |
| `hydra`        | Brute-force login attempts           |
| `msfconsole`   | Exploitation framework               |
| `john`         | Password hash cracking               |
| `hashcat`      | GPU-accelerated hash cracking        |
| `gzip`         | Wordlist decompression               |

---

## 🗝️ Key Achievements

- Successful exploitation of **ProFTPD 1.3.3c backdoor**
- Root shell access on both target VMs
- Dumped and cracked a SHA-512 password hash
- Demonstrated SSH brute-forcing, privilege escalation, and payload selection

---

## 📎 How to Reproduce

1. Set up both VMs in `host-only` network mode.
2. Use `nmap` and `arp-scan` to identify target IPs.
3. Follow exploitation steps as outlined in the PDF report.
4. Use `john` or `hashcat` with `rockyou.txt` for password cracking.

---

## 📄 License

This penetration testing was conducted in a controlled lab environment for educational purposes only.

> 🛑 **Unauthorized access or exploitation of real-world systems is illegal. Always perform pentesting with permission.**

---

## 🙌 Acknowledgements

- Offensive Security (Kali Linux)
- VulnHub community VMs
- Rapid7 Metasploit Framework
- Hashcat & John developers

