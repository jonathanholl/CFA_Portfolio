[README.md](https://github.com/user-attachments/files/25875523/README.md)
# 🔍 CFA Portfolio — Digital Forensics Case Studies

**Jonathan Holl** | Computer Forensics Analyst Candidate  
B.S. Computer Science — Cybersecurity Focus  
San Antonio, TX

---

## About This Repository

This portfolio demonstrates professional digital forensics skills developed through academic training and independent case study work. Each project simulates a real-world investigation workflow following industry-standard procedures used by federal and law enforcement forensic analysts.

The case studies cover the full investigative lifecycle: from evidence seizure and forensic imaging through analysis, deleted file recovery, OSINT development, and court-ready documentation.

---

## 📁 Case Studies

### Case TT-2024-047 — Operation Timber Trail
> *Homeland Security–style digital forensic investigation*

**[View Case Study →](./forensics-portfolio-case-study.html)**

A simulated HSI digital forensics examination of a seized hard drive. A deleted photograph of a distinctive piece of furniture becomes the central investigative lead, ultimately linking the subject to a local business through EXIF metadata, browser artifacts, and open-source intelligence.

**Skills demonstrated:**
- Forensic evidence acquisition and chain of custody documentation
- Write blocker procedure and forensic imaging with FTK Imager
- MD5 / SHA-256 hash verification
- File system analysis using Autopsy and Sleuth Kit
- Deleted file recovery from unallocated space via file carving
- EXIF metadata extraction with ExifTool
- Timeline analysis and keyword searching
- OSINT pivot from digital artifact to physical location
- Professional forensic report writing

**Tools used:**  
`Autopsy` `FTK Imager` `Sleuth Kit` `Bulk Extractor` `ExifTool` `Foremost` `PhotoRec`

---

## 🛠 Core Competencies

| Domain | Skills |
|---|---|
| Evidence Handling | Seizure procedures, chain of custody, write blocking, forensic imaging |
| File System Analysis | NTFS/FAT, MFT analysis, deleted file identification, slack space |
| File Recovery | MFT carving, file signature carving, unallocated space analysis |
| Metadata Analysis | EXIF extraction, GPS correlation, timestamp analysis |
| Network & Web Artifacts | Browser history, cached files, URL extraction |
| OSINT | Reverse image search, business registry lookup, entity link analysis |
| Documentation | Evidence logs, forensic reports, chain of custody forms |
| Programming | Python, Bash scripting for forensic automation |

---

## 🎓 Education & Background

**B.S. Computer Science — Cybersecurity Concentration**  
Relevant coursework: Digital Forensics, Network Security, Cryptography, Operating Systems, Database Systems

**Certifications / Training in Progress**
- CompTIA Security+
- FEMA / DHS preparatory coursework

---

## ⚙️ Lab Environment

Case studies are conducted using the following setup:

- **OS:** Windows 10 / Kali Linux (forensic workstation)
- **Primary Tools:** Autopsy 4.x, FTK Imager, Sleuth Kit CLI
- **Reference Datasets:** NIST CFReDS forensic disk images (cfreds.nist.gov)
- **Write Blocking:** Simulated via read-only mount / hardware write blocker procedure

---

## 📄 Disclaimer

> All case studies in this repository are **entirely simulated** and created for educational and portfolio purposes only. No real investigation data, personally identifiable information, or classified material is contained herein. Scenario names, case numbers, businesses, and individuals are fictional. This work does not represent the position or methodology of any government agency.

---

## 📬 Contact

**GitHub:** [github.com/jonathanholl](https://github.com/jonathanholl)

---

*Portfolio actively updated as new case studies are completed.*
