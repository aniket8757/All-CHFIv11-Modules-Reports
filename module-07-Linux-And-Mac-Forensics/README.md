# 🐧 Linux Forensics

## 📌 Overview
Linux Forensics focuses on investigating Linux-based systems to uncover digital evidence.  
It involves analyzing system logs, user activity, processes, memory, and file system artifacts to detect intrusions, malware, or insider threats.  
Due to Linux’s widespread use in servers and security infrastructure, Linux forensics is crucial in DFIR (Digital Forensics & Incident Response).

---

## 🎯 Objectives
- Understand Linux file systems (EXT4, XFS, Btrfs, etc.)
- Investigate system and authentication logs
- Perform memory and process forensics
- Recover deleted or hidden files
- Detect persistence techniques and rootkits
- Document forensic findings

---

## 🔍 Key Linux Artifacts
- **/var/log/** → System, authentication, kernel, and service logs  
- **/etc/passwd & /etc/shadow** → User accounts and authentication data  
- **Bash History (.bash_history)** → Command execution history  
- **Crontab & Systemd Services** → Persistence mechanisms  
- **Proc (/proc/)** → Running processes and system info  
- **File System Journals** → Metadata and recovery clues  

---

## 🛠️ Tools for Linux Forensics
- **Autopsy / Sleuth Kit** – File system analysis  
- **Volatility / LiME** – Memory acquisition & forensics  
- **Log2Timeline (Plaso)** – Timeline analysis  
- **Chkrootkit / rkhunter** – Rootkit detection  
- **Foremost / Scalpel** – File carving & recovery  
- **strings, grep, awk** – Native Linux analysis commands  

---

## ⚙️ Linux Forensics Process
1. **Preparation** → Define scope, preserve system state  
2. **Acquisition** → Disk imaging (dd, dc3dd), memory capture (LiME)  
3. **Preservation** → Validate hashes (MD5, SHA256)  
4. **Analysis** → Logs, processes, artifacts, persistence mechanisms  
5. **Correlation** → Connect user actions & attacker footprints  
6. **Reporting** → Document findings with evidence  

---

## 📂 Case Study Examples
- Detecting brute-force SSH attempts via **/var/log/auth.log**  
- Investigating malware persistence through **crontab entries**  
- Identifying insider threats via **.bash_history**  
- Memory analysis of running rootkits with **Volatility**  

---

## 📘 References
- [Linux Forensics by Philip Polstra](https://www.amazon.com/Linux-Forensics-Philip-Polstra/dp/0128183822)  
- [SANS DFIR Linux Resources](https://www.sans.org)  
- [Volatility Foundation](https://www.volatilityfoundation.org/)  

---

## 🏷️ Tags
`linux-forensics` `digital-forensics` `dfir` `incident-response` `memory-forensics` `log-analysis` `cybersecurity` `rootkit-detection`

---


# 🍏 Mac Forensics

## 📌 Overview
Mac Forensics involves investigating Apple’s macOS systems to uncover evidence of malicious activity, insider threats, or cybercrimes.  
It includes analyzing system logs, user artifacts, memory, and file system structures like **APFS (Apple File System)** and **HFS+**.  
Due to macOS’s unique architecture, specialized forensic approaches and tools are required.

---

## 🎯 Objectives
- Understand macOS file systems (APFS, HFS+)  
- Investigate macOS logs, plists, and user artifacts  
- Perform acquisition of macOS disks and memory  
- Analyze persistence and malware mechanisms  
- Recover deleted files and track user activities  
- Generate forensic reports for legal evidence  

---

## 🔍 Key macOS Artifacts
- **Unified Logs (log show)** → System and application logs  
- **Property Lists (.plist)** → App settings, user preferences  
- **Keychain** → Credentials and encryption keys  
- **Quarantine Events** → Downloaded files history  
- **Spotlight Database** → File indexing and searches  
- **Time Machine Backups** → Historical data  
- **User Home Directory (~/Library/)** → Safari, Mail, App data  

---

## 🛠️ Tools for Mac Forensics
- **Autopsy / Sleuth Kit** – File system analysis  
- **MacQuisition** – macOS forensic imaging  
- **BlackLight** – Mac & iOS forensic analysis  
- **Volatility (Mac plugins)** – Memory forensics  
- **iBackup Viewer** – iTunes/iCloud backups  
- **log show / fsevents** – Native macOS forensic logs  

---

## ⚙️ Mac Forensics Process
1. **Preparation** → Collect tools, ensure chain of custody  
2. **Acquisition** → Forensic imaging with MacQuisition / dd  
3. **Preservation** → Use hashing for integrity verification  
4. **Analysis** → Logs, plists, spotlight, quarantine events  
5. **Correlation** → Match activity with attacker/user timeline  
6. **Reporting** → Provide documented evidence  

---

## 📂 Case Study Examples
- Detecting malware persistence through **LaunchAgents/Daemons**  
- Tracking user downloads via **Quarantine Events Database**  
- Identifying search history via **Spotlight indexing**  
- Analyzing stolen credentials in **Keychain data**  

---

## 📘 References
- [MacOS Forensics by Jaron Bradley](https://www.amazon.com/macOS-Forensics-Analyst-Jaron-Bradley/dp/1098110634)  
- [BlackBag Technologies](https://www.blackbagtech.com/)  
- [SANS DFIR macOS Resources](https://www.sans.org)  

---

## 🏷️ Tags
`mac-forensics` `digital-forensics` `dfir` `incident-response` `memory-forensics` `apfs` `hfs+` `plist-analysis` `cybersecurity`

---

