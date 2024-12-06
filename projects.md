---
layout: default
title: Projects
---

# Projects

## 1. Automated Pentest Toolbox
The **Automated Pentest Toolbox** is a Python-based suite designed to automate penetration testing tasks such as network analysis, vulnerability detection, and brute-force attacks.

### Key Features
- Comprehensive scanning for footprinting and network analysis.
- Automated vulnerability detection using Nmap and CVE databases.
- Directory and web application enumeration.
- Brute-force capabilities for FTP and SSH services.

### Technologies Used
- **Programming Language:** Python  
- **Tools & Libraries:** Nmap, Python CLI, Docker (optional)

### Usage
Clone the repository, install dependencies, and execute modules to automate your penetration testing workflow:
```bash
git clone https://github.com/K4ZUM4KIRYU/PenTestToolBox.git
cd PenTestToolBox
pip install -r requirements.txt
python3 nmap_scan.py --target 192.168.1.1/24 --ports 1-65535
```
