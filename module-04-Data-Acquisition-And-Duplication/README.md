# Data Acquisition and Duplication

## 📌 Overview
**Data Acquisition and Duplication** is a critical step in computer forensics where investigators collect and create exact copies (duplicates) of digital evidence. This ensures that the original data remains intact while allowing forensic analysis to be performed on the copies without compromising evidence integrity.

---

## 🛠️ Objectives
- Acquire data from digital devices in a **forensically sound** manner.
- Preserve the integrity and authenticity of evidence.
- Maintain a **Chain of Custody** for legal admissibility.
- Ensure **bit-by-bit duplication** for accuracy.

---

## 🔑 Key Concepts

### 1. Data Acquisition
- The process of **collecting data** from a suspect system or storage media.
- Can include hard drives, SSDs, USB devices, mobile phones, memory, or network traffic.
- Must follow strict procedures to prevent **modification or loss of data**.

### 2. Data Duplication
- Creating a **forensic image** (bit-by-bit copy) of the acquired data.
- Used for investigation while the original evidence is preserved.
- Can be performed using specialized tools and hardware write blockers.

---

## 🧰 Types of Acquisition

### 🔹 1. Static Acquisition
- Performed when the device is powered off.
- Typically involves removing the storage media and imaging it.
- Safer, as no system changes occur.

### 🔹 2. Live Acquisition
- Conducted when the system is running.
- Captures volatile data (RAM, running processes, network connections).
- Useful in cases involving malware or rootkits.

### 🔹 3. Logical Acquisition
- Captures specific files or directories.
- Faster but not as complete as bit-stream imaging.

### 🔹 4. Bit-Stream (Forensic Imaging)
- Creates an **exact sector-by-sector copy** of the entire drive or partition.
- Preserves deleted files, slack space, and hidden data.

---

## ⚙️ Tools for Acquisition and Duplication
- **FTK Imager**
- **EnCase Forensic Imager**
- **X-Ways Forensics**
- **dd (Linux command-line tool)**
- **Guymager**
- **Clonezilla**
- **dc3dd (enhanced dd for forensics)**

---

## 📂 Chain of Custody
- Each step in acquisition and duplication must be documented:
  - Who handled the evidence.
  - When and how it was acquired.
  - Where it was stored.
- Prevents claims of tampering or mishandling.

---

## ✅ Best Practices
- Always use **write blockers** when imaging storage devices.
- Work only on **forensic copies**, never on the original evidence.
- Verify integrity using **hash values (MD5, SHA1, SHA256)**.
- Document every action taken during acquisition.

---

## 📖 References
- NIST SP 800-101: *Guidelines on Mobile Device Forensics*
- ISO/IEC 27037: *Digital Evidence Acquisition Standards*
- NIST SP 800-86: *Guide to Integrating Forensic Techniques into Incident Response*

---

## 📌 Conclusion
**Data Acquisition and Duplication** form the foundation of digital forensic investigations. By following best practices, using reliable forensic tools, and maintaining strict evidence handling procedures, investigators can ensure the integrity and admissibility of digital evidence in court.

