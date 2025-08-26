# 🕵️‍♂️ Windows Forensics

## 📌 Overview
Windows Forensics involves the investigation and analysis of Windows-based systems to uncover digital evidence related to security incidents, cybercrimes, insider threats, or policy violations.  
It focuses on identifying, preserving, analyzing, and presenting evidence stored in Windows operating systems, including event logs, registry data, memory dumps, and file systems.

---

## 🎯 Objectives
- Understand Windows system architecture and artifacts
- Perform forensic acquisition of Windows machines
- Analyze Windows event logs and registry
- Examine volatile data such as memory and running processes
- Detect persistence mechanisms, malware, and anti-forensic techniques
- Document and present forensic findings

---

## 🔍 Key Windows Artifacts
- **Event Logs** → Security, System, Application, and Custom Logs  
- **Registry Hives** → SAM, SYSTEM, SOFTWARE, NTUSER.DAT  
- **Prefetch Files** → Application execution history  
- **Recent Files & Jump Lists** → User activity tracking  
- **Pagefile & Hibernation File** → Memory data persistence  
- **Recycle Bin** → Deleted files recovery  
- **Browser Artifacts** → History, Cookies, Cache  

---

## 🛠️ Tools for Windows Forensics
- **FTK Imager** – Disk acquisition & analysis  
- **Autopsy/Sleuth Kit** – Comprehensive forensic suite  
- **Volatility / Rekall** – Memory forensics  
- **Windows Event Viewer** – Event log analysis  
- **Registry Explorer / RegRipper** – Registry analysis  
- **Prefetch Parser** – Application execution artifacts  
- **X-Ways Forensics / EnCase** – Professional forensic suites  

---

## ⚙️ Windows Forensics Process
1. **Preparation** → Define scope, collect tools, establish chain of custody  
2. **Acquisition** → Create forensic images of drives and memory  
3. **Preservation** → Ensure integrity using hashing (MD5, SHA1, SHA256)  
4. **Analysis** → Examine artifacts, logs, and evidence sources  
5. **Correlation** → Connect user actions with system evidence  
6. **Reporting** → Document findings with evidence screenshots  

---

## 📂 Case Study Examples
- Detecting unauthorized logins via **Security Event Logs**  
- Recovering deleted files from **NTFS file system**  
- Identifying persistence via **Registry Run Keys**  
- Analyzing malware execution through **Prefetch files**  

---

## 📘 References
- [Windows Forensics and Incident Recovery by Harlan Carvey](https://www.amazon.com/Windows-Forensic-Analysis-Toolkit-4E/dp/0124171575)  
- [SANS DFIR Windows Forensics Resources](https://www.sans.org)  
- [Volatility Foundation](https://www.volatilityfoundation.org/)  

---

## 🏷️ Tags
`windows-forensics` `digital-forensics` `dfir` `incident-response` `memory-forensics` `registry-analysis` `event-log-analysis` `cybersecurity` `malware-investigation`

---

