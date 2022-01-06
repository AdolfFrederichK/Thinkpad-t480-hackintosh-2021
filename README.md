# Thinkpad-t480-hackintosh-2021
Thinkpad T480 Hackintosh

catalina 10.15 working

# Hardware 
i7 8550U + intel UHD 620  

1366x768 screen touch  

intel Ethernet AC 8265  

Synaptics TrackPoint  

Synaptics Fingerprint Reader  

2x8 GB RAM  

WD BLACK SN750（1TB）  

# Before installation

**Security**
* Security Chip Disabled
* Memory Protection -> Execution Prevention Enabled
* Virtualization -> Intel Virtualization Technology Enabled
* Virtualization -> Intel VT-d Feature Enabled
* Anti-Theft -> Computrace -> Current Setting Disabled
* Secure Boot -> Secure Boot Disabled
* Intel SGX -> Intel SGX Control Disabled
* Device Guard Disabled
* Startup

* UEFI/Legacy Boot UEFI Only
* CSM Support No
* Thunderbolt

* Thunderbolt BIOS Assist Mode Disabled
* Wake by Thunderbolt(TM) 3 Disabled
* Security Level User Authorization
* Support in Pre Boot Environment -> Thunderbolt(TM) device Enabled


# Working
* Keyboard & TrackPoint/TrackPad (as mouse)

* Screen brightness & brightness shortcut keys

* Basic audio including speaker, internal mic, headphone jack

* Touchscreen (multi) (10.15)

* Camera

* All USB ports

* HDMI video port

* Sleep/resume

* wifi, bluetooth

# Resources used:
使用的EFI文件 https://github.com/nhoxnho1212/thinkpad-t480-hackintosh （EFI-10.15 CLOVER）

网卡驱动 AirportItlwm_v2.1.0_stable_Catalina.kext https://github.com/OpenIntelWireless/itlwm/releases  

