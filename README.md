<h1 align="center"> macOS on HP EliteBook 820 G3 </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/HP-EliteBook-820-G3-Hackintosh/blob/main/Images/HP%20EliteBook%20820%20G3.png" width="400" alt="EliteBook 820 G3">
</p>

<h4 align="center"> OpenCore config for Hackintosh HP EliteBook 820 G3 </h4>

<p align="center">
<a href="https://www.apple.com/macos/monterey/">
  <img src="https://img.shields.io/badge/macOS-Monterey-purple" width="165"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg/releases">
  <img src="https://img.shields.io/badge/OpenCore-0.9.1-9cf" width="155"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg" width="115"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=white" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-red?logo=YouTube&logoColor=white" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-white?logo=PayPal" width="140"/> </a>

## Contents
  - [Screenshots](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#screenshots-)
  - [Original Hardware](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#original-hardware--)
  - [Modifications](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#modifications--)
  - [macOS Update History](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#macos-update-history)
  - [What's working](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#whats-working--)
  - [What's you have to do](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#whats-you-have-to-do--)
  - [Kexts Used](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#kext-used)
  - [SSDTs Used](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#ssdt-used)
  - [Changelog](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#changelog)
  - [How to make it better?](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#how-to-make-it-better)
    - [Advanced Resolution](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#advanced-resolution)
    - [Thinkpad's Click and Trackpad](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#thinkpads-click-and-trackpad)
    - [DW1820A Windows Driver](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#dw1820a-windows-1011-driver)
  - [Credits](https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh#credits)
  - [Donate](https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Bağış.md)
  
## Screenshots 📷

<details>
<summary>Monterey</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/macOS%20Monterey.png">
</p>
</details>

## Original Hardware  💻

Type | Spec | Status
:---------|:---------|:----------
Model Name      | HP EliteBook 820 G3 | ✅
CPU              | Intel® Core™ i5-6200U CPU @ 2.30GHz | ✅
RAM           | SK Hynix HMA851S6AFR6N-UH 8(4+4) GB 2133 MHz DDR4 | ✅
Internal Graphics Card | Intel® HD Graphics 520 | ✅
Wi-Fi             | Intel® Dual Band Wireless-AC 8260 | ✅
Ethernet          | Intel® Ethernet Connection I219-V | ✅
Audio       | Conexant | ✅
 
## macOS Update History
- ✅ macOS Monterey 12.3

## What's working  💻
  
Type | Status
:---------|:---------
Turbo boost and CPU frequency stage |  ✅  
Intel HD Graphics 520              |  ✅  
Brightness control                  |  ✅  
HDMI                                |  ✅  
Audio Conexant            |  ✅  
Ethernet I219-V            |  ✅  
Intel Wireless-AC 8260         |  ✅  
USB Ports (with Port Mapping)        |  ✅  
Touchpad (14 gestures are working)   |  ✅  
Battery status   |  ✅  
Camera   |  ✅  
 
## What's you have to do  💻
  
Type | Info | Status
:---------|:---------|:----------
SMBIOS Settings  | With [GenSMBIOS] you should definitely set your SMBIOS settings and ROM value for iCloud and Apple services. ROM value is your ethernet MAC address. Be sure your ethernet is en0 in Hackintool. |  ⚠️

## How to make it better?
<details>  
  <summary><h4>Advanced Resolution</h4></summary>

- Use RDM for 1600x900 resolution which i am using currently. 
  - [Download RDM](https://disk.yandex.com.tr/d/D9TtO3QEqAbtww)
 
## How to Use?
- Download and open RDM.app. Follow images below.
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/RDM/RDM%201680x1050.png" alt="1680x1050" width="600"> 

- Set resolution 1680x1050.
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/RDM/RDM%20Edit%20Button.png" alt="RDM Edit Button" width="600"> 

<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/RDM/RDM%20Resolution%20Settings.png" alt="RDM Resolution Settings" width="600"> 

- Set what resolution you want. Click save, enter password and reboot.
<img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/Images/RDM/RDM%201600x900.png" alt="1600x900" width="600">  

- Open RMD and select resolution what you want. This is only once.
</details>  
  
      
## Credits
  
 - [Dortania](https://dortania.github.io) for developing OpenCore.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [RehabMan](https://github.com/RehabMan) for battery patches.
 - [Sniki](https://github.com/Sniki) for USB kext.
 - And anyone else that helped to develop and improve hackintoshing.

<h1 align="center"> Donate - Bağış </h1>
<p align="center">
<a href="https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusfklncc/blob/main/Resources/Donate.png" width="300">
