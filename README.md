# X99DeluxeII
All my files (including 3rd party work) for X99 Deluxe II based hack. Works great.

Currenly used Clover version: **Clover_v2.4k_r4411** [clover](https://sourceforge.net/projects/cloverefiboot/)

## **Setup:**
- Asus X99 Deluxe II Rev 1.02 - latest BIOS, locked MSR [asus](https://www.asus.com/us/Motherboards/X99-DELUXE-II/)
- i7 5820K 3.3Ghz > O.C. 3.8Ghz (XCPM patches included)
- nVidia 1080 Ti (nVidia WEB Drivers)
- G.Skill Trident Z RGB 64GB 3200Mhz > O.C. 3600MHZ
- Seasonic Prime Titanium 850W

- Samsung 960 PRO 512GB
- Samsung 850 EVO 250G
- Seagate FireCuda Laptop SSHD 2TB

- macOS version - 10.13.3 (17D102) patches for 10.13.4 beta included

## **Drivers & Patches**
**Audio:**
- VoodooHDA 2.9.0 Clover-V10 - works great even for DisplayPort and HDMI audio

**Network:**
- WiFi - OOB
- BT - BrcmBluetoothInjector.kext [repo](https://github.com/the-darkvoid/BrcmPatchRAM)
- Intel® I218V - IntelMausiEthernet.kext [repo](https://github.com/Mieze/IntelMausiEthernet)
- Intel® I211-A - SmallTreeIntel82576.kext

**USB**
- X99_Injector_USB_3.kext

**ACPI Tables**
- Piker Alpha ssdtPRGen.sh [repo](https://github.com/Piker-Alpha/ssdtPRGen.sh)

**XCPM**
- Piker Alpha Patches
- VoodooTSCSync.kext
- MacPro Vectors through - freqVectorsEdit.sh [repo](https://github.com/Piker-Alpha/freqVectorsEdit.sh)
X86PLatform.kext loaded, native PM

**NVMe**
- Piker Alpha Patch & RehabMan fix

## **BIOS Settings:**
- CMS - Disabled
- Secure Boot - Other OS

## **System Services**
**iMessage and iCloud services:**
use iMessageDebug for extract ROM and MLB(Board Serial Number) from
"real" Mac machine then insert your numbers to config.plist

**never install OS with those numbers** otherwise Apple will block them
and you will have to call Apple support (and that is horrible thing trust me).

Read [iMessage explaned](http://www.insanelymac.com/forum/topic/298027-guide-aio-guides-for-hackintosh/page-9#entry2060421)
