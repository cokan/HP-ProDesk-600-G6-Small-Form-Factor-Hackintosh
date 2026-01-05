# HP-ProDesk-600-G6-SFF-Hackintosh
# System configuration
|Model  |iMac20,1  |Version	|macOS Sequoia 15.73|
| :----- | :----- |:----- |:----- |
|Processor |Intel Core i3-10100	|Coffee Lake	|Intel HD Graphics 630|
|Memory	   |Samsung 3200MHz DDR4 32GB	|OS Disk	|WD Blue SN5000 NVMe 1TB|
|Audio	   |Realtek ALC222 -11	|WiFi/Bluetooth	|Intel Wifi-6 AX201|
|BIOS      |HP Inc. Q470  | Opencore| release 1.0.6


# BIOS

BIOS Settings : 
 Security :  TPM Embedded, TPM Device : Enabled BIOS Sure Start : All disabled, just "Dynamic Runtime Scanning of Boot Block" checked Secure Boot : All disabled Intel Software Guard : Disabled  Advanced : Boot options : Startup Delay : 0 Enabled : Fast boot; USB Storage Boot, Audio Alerts during boot, UEFI Boot Order : 1) OpenCore HP Sure Recover : All disabled System Options : Enabled : Turbo-Boost, Hyperthreading, VTx Built-IN Devices : Enabled : Embedded LAN Controller, Audio Device, Internal Speakers, M2 USB/Bluetooth, Video Memory


# N. Log

- 1. Obtain system report [Hardware-Sniffer](https://github.com/lzhoang2801/Hardware-Sniffer)
- 2. Create EFI file [OpCore-Simplify](https://github.com/lzhoang2801/OpCore-Simplify)
- 3. Modify and update EFI [OCAT](https://github.com/ic005k/OCAuxiliaryTools)
- 3. Create system USB drive [macOS Installer](https://support.apple.com/zh-cn/101578) [balenaEtcher imaging tool](https://etcher.balena.io/)
- 4. Wi-Fi driver patch [OCLP-Mod](https://github.com/laobamac/OCLP-Mod)
- 5. Check system status [Hackintosh](https://github.com/benbaker76/Hackintool)
