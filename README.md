# General Info
Code, EFI, and Other Items that I Used To Dual Boot MacOS Sonoma 14.5 and Windows 11 With UEFI Secure Boot Enabled on OpenCore 1.0.0
- Use this as a base to find any problems with your EFI if you use the same hardware!
- Tip: When updating open Core or any .efi file resign them through your BIOS!
- ### iMessages, FaceTime and other iServices might not work due to airportitlwm! Use itlwm + Heliport if needed!
## Specs:
- Case: Fractal Design Ridge
- CPU: Intel Core i7-13700K

- GPU: PowerColor RX 6700 XT
- MOBO: ASUS ROG STRIX B760-I Gaming WiFi
- RAM: 32 GB DDR5 5600 MHz
- SSD 1: (Windows) WD_BLACK SN850X
- SSD 2: (MacOS) WD_BLACK SN850X
- Ethernet: Intel Ethernet Controller I226-V (Built-in)
- Wi-Fi: Intel Wi-Fi 6E AX211 160MHz (Built-in)
- Bluetooth: Built-in
- BIOS/Drivers: Latest As of July 24, 2024
## Tools:
[OpenCore](https://github.com/acidanthera/OpenCorePkg) (Bootloader for MacOS)

[ProperTree](https://github.com/corpnewt/ProperTree) (Edit .plist files)

[SSDTTime](https://github.com/corpnewt/SSDTTime) (Making SSDTs)

[GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) (Making Hardware Info for MacOS)

[Brigadier](https://github.com/timsutton/brigadier) (Installing Boot Camp For Windows Dual Boot)

[USBMap](https://github.com/corpnewt/USBMap) (Making USB Ports available in MacOS)

[CPU-Name](https://github.com/corpnewt/CPU-Name) (Showing Correct CPU Name in MacOS)

## Kexts:
Search Up the Kexts if you don't know where to find them!
- AirportItlwm
- AppleIGC
- BlueToolFixup
- CPUTopologyRebuild
- CPUTscSync
- CtInaAHCIPort
- IntelBluetoothFirmware
- IntelBTPatcher
- Lilu
- NootRX
- RestrictEvents
- NVMEFix
- SMCProcessor
- SMCRadeonSensors
- SMCSuperIO
- USBMap
- VirtualSMC

## Guides:
### [Dortania's OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/)

[perez987 - OpenCore and UEFI Secure Boot: The Easy Way](https://github.com/perez987/OpenCore-and-UEFI-Secure-Boot/blob/main/guide/The%20easy%20way.md) (I didn't use this guide but it is the same thing I did)

[profzei - Enable BIOS Secure Boot with OpenCore](https://github.com/profzei/Matebook-X-Pro-2018/wiki/Enable-BIOS-Secure-Boot-with-OpenCore)

[CorpNewt - Hackintosh Tips and Tricks](https://github.com/corpnewt/Hackintosh-Tips-And-Tricks) (I didn't need to use this but it might be helpful!)

