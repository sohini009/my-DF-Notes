# VirusTotal Analysis Report

## 📁 File Info
- **Filename:** LBpiy.exe
- **Size:** 902.00 KB
- **File Type:** PE Executable
- **Hashes:**
  - **MD5:** ae2a513b61febc225d5e374ab22dba75
  - **SHA1:** 4a3d38e49b7bbd442fe3f9bab16b8fb1
  - **SHA256:** ae2a513b61febc225d5e374ab22dba754a3d38e49b7bbd442fe3f9bab16b8fb1

## 🧪 Detection
**Detection Ratio:** 55/72 security vendors flagged this file as malicious.

| Engine                | Detection |
|-----------------------|-----------|
| AhnLab-V3             | Malware/Win.Kryptik.C5784104 |
| Alibaba               | Trojan:MSIL/Taskun.cf3a01e2 |
| AliCloud              | Trojan:MSIL/Egairtigado.Gen |
| ALYac                 | Trojan.GenericKDZ.112786 |
| Arcabit               | Trojan.Generic.D1B892 |
| Arctic Wolf           | Unsafe |
| Avast                 | Win32:MalwareX-gen [Pws] |
| AVG                   | Win32:MalwareX-gen [Pws] |
| Avira (no cloud)      | TR/AD.SnakeStealer.lzrbr |
| BitDefender           | Trojan.GenericKDZ.112786 |
| CrowdStrike Falcon    | Win/malicious_confidence_100% (D) |
| DeepInstinct          | MALICIOUS |
| DrWeb                 | Trojan.Packed2.49940 |
| Elastic               | Malicious (high Confidence) |
| ESET-NOD32            | A Variant Of MSIL/Kryptik.AOBM |
| Fortinet              | MSIL/Formbook.HDZY!tr |
| GData                 | Trojan.GenericKDZ.112786 |
| Google                | Detected |
| Huorong               | TrojanSpy/MSIL.Stealer.js |
| Kaspersky             | HEUR:Trojan.MSIL.Taskun.gen |
| Malwarebytes          | Trojan.MalPack.PNG.Generic |
| McAfee Scanner        | Ti!AE2A513B61FE |
| Microsoft             | Trojan:Win32/Egairtigado!rfn |
| Panda                 | Trj/Chgt.AD |
| QuickHeal             | Trojan.MSIL |
| Sangfor Engine Zero   | Infostealer.Msil.Taskun.Vxqn |
| Sophos                | Troj/Krypt-AQM |
| Symantec              | Scr.Malcode!gdn34 |
| TrendMicro            | TrojanSpy.Win32.NEGASTEAL.YXFG5Z |
| ZoneAlarm             | Troj/Krypt-AQM |
| … *(others omitted for brevity)* | ... |

**Popular Threat Labels:**
- `trojan.msil/taskun`
- `egairtigado`
- `msil`
- `trojan`

## 📡 Network Indicators
- Potentially connects to **unknown remote servers** (no specific domains or IPs listed in provided data).
- Possible data exfiltration behavior.

## 📊 Behavioral Summary
- **Technical Flags:**  
  - Detects debug environment  
  - Spreader capability  
  - Accesses clipboard data  
  - Uses long sleep calls (anti-sandbox technique)  
  - Calls WMI for system information  
  - Packed and obfuscated  
- **Sandbox Indicators:** Possible credential theft, keylogging, and data exfiltration.

## 🗣️ Community Insight
- **Community Score:** -12  
- Users generally flagged as malicious and unsafe.  
- No positive reputation feedback.

## 🔐 Public Link
- [VirusTotal Public Scan Link](https://www.virustotal.com/gui/file/ae2a513b61febc225d5e374ab22dba754a3d38e49b7bbd442fe3f9bab16b8fb1)

## 🖼️ Screenshots
*(Include your VirusTotal dashboard and scan results screenshots here)*
-![VT Detection Screenshot] (Screenshots/Screenshot%201.png)
-![VT Vendors List] (Screenshots/Screenshot%202.png)
-![VT Detection Screenshot] (Screenshots/Screenshot%203.png)
-![VT Vendors List] (Screenshots/Screenshot%204.png)
