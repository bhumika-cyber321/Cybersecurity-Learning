# 🔐 Nmap Network Scanning Lab

## 📌 Project Overview
This project is part of my Cybersecurity learning journey. It focuses on understanding network scanning and discovering network services using Nmap.

## 🎯 Project Objectives
- Understand Nmap and its purpose.
- Learn basic network scanning.
- Identify open ports on an authorized test system.
- Understand service detection.
- Develop practical networking and cybersecurity skills.

## 🛠️ Tools & Environment
- Tool: Nmap
- Operating System: Windows 11
- Level: Beginner
- Lab Target: Localhost (127.0.0.1)

## 💻 Basic Nmap Commands

### 1. Check Nmap Version
```bash
nmap --version
```

### 2. Basic Localhost Scan
```bash
nmap 127.0.0.1
```

### 3. Host Discovery
```bash
nmap -sn 127.0.0.1
```

### 4. Service Version Detection
```bash
nmap -sV 127.0.0.1
```

## 📖 Command Explanation
- `nmap`: Starts the Nmap tool.
- `-sn`: Performs host discovery without a port scan.
- `-sV`: Attempts to identify services and their versions.
- `127.0.0.1`: Refers to the local computer (localhost).

## 📊 Practical Results
Results will be documented after performing the lab.

- Target IP: 127.0.0.1
- Open Ports: To be documented
- Detected Services: To be documented
- Observations: To be updated after testing

## 📚 What I Learned
- Basic network scanning concepts.
- Introduction to port scanning.
- Understanding Nmap commands.
- Basics of service detection.

## ⚠️ Security Disclaimer
All practical activities must be performed only on systems that I own or have explicit permission to test.

## 🚀 Future Improvements
- Learn advanced Nmap options.
- Practice in a controlled home lab.
- Document more network security experiments.

---
⭐ Learning | Practicing | Improving

**Author:** Bhumika  
**Field:** Cybersecurity
## Practical Results — Windows 11

**Environment:**
- Operating System: Windows 11
- Tool: Nmap
- Target: 127.0.0.1 (Localhost)
- Scan Date: 17 November 2026

### 1. Basic Port Scan

Command:
`nmap 127.0.0.1`

Results:
- Host status: Up
- Port 135/tcp: Open — MSRPC
- Port 445/tcp: Open — Microsoft-DS
- 998 TCP ports: Closed

### 2. Service Version Detection

Command:
`nmap -sV 127.0.0.1`

Results:
- Port 135: Microsoft Windows RPC
- Port 445: microsoft-ds? (Exact service identification uncertain)
- OS information: Windows

### 3. Host Discovery

Command:
`nmap -sn 127.0.0.1`

Results:
- Host status: Up
- Active hosts: 1
- Scan completed successfully.

### What I Learned

- How to perform a basic Nmap scan.
- How to identify open and closed ports.
- How to detect services.
- How to perform host discovery.
- How to read Nmap scan results.

**Safety:** All scans were performed against my own computer (localhost).
