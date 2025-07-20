# 🚀 Project Title

**One-line description** (e.g. “Nmap Vulnerability Scan Report”)

---

## 📋 Overview
- **Tool / Lab**: Nmap / Nikto / Wireshark / Burp Suite / TryHackMe - *Room Name*
- **Target / Scope**: `<IP or domain or room>`
- **Objective**: Exploit / analyze / scan etc.

---

## 🛠️ Tools Used
- Nmap (v7.x)
- Nikto (v2.x)
- Wireshark
- Burp Suite Community / PortSwigger
- TryHackMe CTF room
- (Any other)

---

## 🧰 Lab Setup
- Virtualization: VirtualBox or VMware
- Operating Systems: Kali Linux, Metasploitable2, target VM
- Network Mode: NAT / Host‑only
- Capture or VM files: `/captures` or `/vm`

---

## 🔎 Steps Taken

1. **Recon / Scanning**  
   ```bash
   nmap -sC -sV TARGET_IP -oN nmap_full_scan.txt
