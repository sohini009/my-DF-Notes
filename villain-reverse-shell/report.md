# Villain Framework Reverse Shell Report

## ⚙️ Setup Info
- **Payload**: `windows/reverse_tcp/powershell`
- **LHOST**: 192.168.56.101
- **LPORT**: 4443

## 🔁 Payload Delivery Method
Executed the PowerShell reverse shell payload on the Windows 11 Home target VM via Villain framework.

## 🖥️ Captured Info
- **Hostname**: SOHINI
- **IP Address**: 192.168.56.1
- **User**: sohini\iamsa

## Screenshots
- ![Villain access Screenshot](Screenshots/Screenshot%205.png)
- ![Executing Commands](Screenshots/Screenshot%201.png)
- ![Payload testing in windows](Screenshots/Screenshot%202.png)
- ![System info windows 1](Screenshots/Screenshot%203.png)
- ![System info windows 2](Screenshots/Screenshot%204.png)

## 🔎 Enumeration Performed
```powershell
whoami
# Output:
sohini\iamsa

ipconfig
# Output:
Windows IP Configuration

Ethernet adapter Ethernet:
   Connection-specific DNS Suffix  . :
   Link-local IPv6 Address . . . . . : fe80::161f:eb5e:f039:2d23%18
   IPv4 Address. . . . . . . . . . . : 192.168.56.1
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :

Unknown adapter OpenVPN Data Channel Offload for Surfshark:
   Media State . . . . . . . . . . . : Media disconnected

Wireless LAN adapter Local Area Connection* 1:
   Media State . . . . . . . . . . . : Media disconnected

Wireless LAN adapter Local Area Connection* 2:
   Media State . . . . . . . . . . . : Media disconnected

Wireless LAN adapter Wi-Fi:
   Media State . . . . . . . . . . . : Media disconnected

systeminfo
# Output:
Host Name:                 SOHINI
OS Name:                   Microsoft Windows 11 Home
OS Version:                10.0.26100 N/A Build 26100
OS Manufacturer:           Microsoft Corporation
OS Configuration:          Standalone Workstation
OS Build Type:              Multiprocessor Free
Registered Owner:          iamsajal68@gmail.com
Original Install Date:     06-12-2025, 23:52:16
System Boot Time:          12-08-2025, 00:01:03
System Manufacturer:       HP
System Model:              HP Laptop 15-dy5xxx
System Type:               x64-based PC
Processor(s):              1 Processor(s) Installed.
                           [01]: Intel64 Family 6 Model 154 Stepping 4 GenuineIntel ~1700 Mhz
BIOS Version:              AMI F.20, 03-11-2023
Windows Directory:         C:\WINDOWS
System Directory:          C:\WINDOWS\System32
Boot Device:               \Device\HarddiskVolume1
System Locale:             en-us;English (United States)
Input Locale:              en-us;English (United States)
Time Zone:                 (UTC-05:00) Eastern Time (US & Canada)
Total Physical Memory:     16,955 MB
Available Physical Memory: 4,598 MB
Virtual Memory: Max Size:  18,375 MB
Virtual Memory: Available: 1,441 MB
Virtual Memory: In Use:    16,934 MB
Page File Location(s):     C:\pagefile.sys
Domain:                    WORKGROUP
Logon Server:              \\SOHINI
Hotfix(s):                 3 Hotfix(s) Installed.
                           [01]: KB5065679
                           [02]: KB5062553
                           [03]: KB5063666
Network Card(s):           3 NIC(s) Installed.
                           [01]: OpenVPN Data Channel Offload - Media disconnected
                           [02]: MediaTek MT7921 Wi-Fi 6 802.11ax PCIe Adapter
                                 DHCP Enabled: Yes
                                 IPv4 Address: 172.20.10.2
                                 DHCP Server: 172.20.10.1
                           [03]: VirtualBox Host-Only Ethernet Adapter
                                 IPv4 Address: 192.168.56.1
Virtualization-based security: Running
Secure Boot:               On
Hyper-V Requirements:      A hypervisor has been detected.
```
