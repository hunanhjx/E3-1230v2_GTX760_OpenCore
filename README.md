# E3-1230v2_GTX760_OpenCore
A EFI based on OpenCore for PCs with Intel Ivy Bridge and Nvidia Kepler video card.

## Languages

- **English (Current)**
- [简体中文](https://github.com/hunanhjx/OpenCore-IvyBridge-Kepler/blob/mine/README_zh-Hans.md)
- [繁體中文](https://github.com/hunanhjx/OpenCore-IvyBridge-Kepler/blob/mine/README_zh-Hant.md)

## **WARNING⚠️**

**I am a new hand who completes this by reading the [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/).**

**At least for me, everything works fine.**

**I am not responsible for any damage you made to your device.**

Any comments or suggestions are welcome!!!😄

## Preview image
### Monterey
![image](https://github.com/hunanhjx/OpenCore-IvyBridge-Kepler/raw/mine/PreviewImages/3.png)

### Big Sur
![image](https://github.com/hunanhjx/OpenCore-IvyBridge-Kepler/raw/mine/PreviewImages/2.png)

### Catalina
![image](https://github.com/hunanhjx/OpenCore-IvyBridge-Kepler/raw/mine/PreviewImages/1.png)

## ![GitHub all releases](https://img.shields.io/github/downloads/hunanhjx/E3-1230v2_GTX760_OpenCore/total?color=%23ebb5e4&label=DOWNLOADS&style=for-the-badge)
[![GitHub release (latest by date)](https://img.shields.io/github/downloads/hunanhjx/E3-1230v2_GTX760_OpenCore/latest/total?label=Monterey%20Latest&style=for-the-badge)](https://github.com/hunanhjx/OpenCore-IvyBridge-Kepler/releases/latest)   [![GitHub release (latest by date)](https://img.shields.io/github/downloads/hunanhjx/E3-1230v2_GTX760_OpenCore/0.7.4/total?label=BIG%20SUR&style=for-the-badge)](https://github.com/hunanhjx/OpenCore-IvyBridge-Kepler/releases/0.7.4)   [![GitHub release (latest by date)](https://img.shields.io/github/downloads/hunanhjx/E3-1230v2_GTX760_OpenCore/0.6.2/total?label=Catalina%20and%20older&style=for-the-badge)](https://github.com/hunanhjx/E3-1230v2_GTX760_OpenCore/releases/tag/0.6.2)


## My PC Spec:

    Motherboard Name	Onda P75U
    
    Motherboard Chipset	Intel Panther Point B75, Intel Ivy Bridge
    
    CPU Type	QuadCore Intel Xeon E3-1230 v2, 3500 MHz (35 x 100)
    
    CPU Alias	Ivy Bridge-WS
    
    UEFI Boot	Yes
    
    Video Adapter	nVIDIA GeForce GTX 760 (p2004)
    
    GPU Code Name	GK104-225
    
    Architecture	nVIDIA Kepler
    
    nVIDIA GK104 HDMI/DP @ nVIDIA GK104 - High Definition Audio Controller	PCI
    
    Realtek ALC662 @ Intel Panther Point PCH - High Definition Audio Controller [C1]	PCI
    
    Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter (PHY: Realtek RTL8211/8212)	PCI
    

## Tips

Nvidia graphics drivers are no longer pre-installed in macOS 12, you need to manually install the driver via [Geforce-Kepler-patcher](https://github.com/chris1111/Geforce-Kepler-patcher)

It is recommended to refer to the [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/) to use this EFI.

If your screen is blank after starting the computer, please try to turn off the motherboard power to reset the BIOS.

Please modify it according to the actual situation, such as sound card id, serial number and other parameters.

## Credits

[Acidanthera](https://github.com/acidanthera) for developing [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg)

[dortania](https://github.com/dortania) for writing [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
