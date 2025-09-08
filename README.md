# Ujar_Tech_solution_intership_Tasks
internship task  
Project_01
# 🔐 Password Cracking Challenge using John the Ripper

## 📌 Objective
The purpose of this project is to demonstrate **password cracking techniques** using industry-standard tools such as **John the Ripper** and **Hashcat**.  
By generating password hashes (MD5/SHA1), attempting to crack them with wordlists/rules, and analyzing the results, we identify **weak passwords** and recommend stronger password policies.

⚠️ **Note**: This project is intended strictly for **educational and research purposes**. Do not use these techniques on systems you do not own or have explicit permission to test.

---

## 🛠️ Tools Used
- [John the Ripper](https://www.openwall.com/john/) – Primary password cracking tool  
- [Hashcat](https://hashcat.net/hashcat/) – Alternative GPU-accelerated cracker  
- **Wordlists** – e.g., [rockyou.txt](https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt) or custom lists  
- **Linux/WSL tools** – `openssl`, `md5sum`, `sha1sum` for hash generation  

---

## ⚙️ Installation

### 🔹 Linux (Kali/Ubuntu/Debian)

Project_02
# 🕵️‍♂️ Basic Network Packet Sniffer

## 🌐 Overview
This project implements a **Python-based network packet sniffer** using the **Scapy** library. The sniffer captures live packets from your local network interface, filters them based on protocols (HTTP, FTP, or any other protocol), and logs key details such as IP addresses, ports, and payloads with timestamps.  

This project helps in understanding **network monitoring, packet analysis, and basic cybersecurity concepts**. 🔒

---

## ✨ Features
- 🖥️ Real-time packet capture from your network interface
- 🔍 Protocol filtering (HTTP, FTP, or custom filters)
- 📝 Extracts key fields:
  - Source & Destination IP 🌐
  - Source & Destination Port 🔢
  - Payload / Data 📦
  - Timestamp ⏰
- 💾 Logs all captured packets to a file (`packet_logs.txt`)
- ⚡ Easy command-line execution via a wrapper script

---

## 🛠️ Tools Used
- **Programming Language:** Python 3.x 🐍  
- **Library:** Scapy 🕸️  
- **Operating System:** Kali Linux / Ubuntu Linux 🐧  
- **Terminal Tools:** Bash / Shell 💻  

---

## 🚀 Getting Started

### 📌 Prerequisites
- Python 3.x installed
- Scapy library
- Root privileges to capture network traffic 🛡️

