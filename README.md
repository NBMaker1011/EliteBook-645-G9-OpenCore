# EliteBook-645-G9-OpenCore
HP EliteBook 645 G9 Hackintosh with OpenCore EFI configuration.
### Disclaimer:
This configuration is unstable and has been made for purely experimental/educational purposes.<br>
A hackintosh should only be created for the purpose of testing the macOS system in prevision of the purchase of an original Mac, and should not replace such a device.

## Tested Operating Systems:
- MacOS Sonoma 14.7.3
- MacOS Sequoia 15.3.1 (WiFi works only with [Heliport](https://github.com/OpenIntelWireless/HeliPort))

## Hardware configuration:
- **CPU:** AMD Ryzen 5 5675U
- **RAM:** 32GB DDR4 3200MHz
- **GPU:** Integrated AMD Radeon RX (512MB VRam)
- **SSD:** Western Digital SN730 512GB
- **Display:** Full HD Touchscreen Display (1920x1080)
- **Ethernet:** Realtek RTL8168 Gigabit Ethernet
- **WiFi:** Intel Dual Band Wireless AC8265
- **Audio:** AMD/Realtek High Definition Audio
- **No fingerprint sensor**

## Bios configuration:
Set video memory allocation to: Automatic<br>
Temporarily disable secure boot.
## What works:
- Trackpad with gestures
- Touchscreen with gestures
- Keyboard with fn keys
- Ethernet
- Wi-Fi
- Bluetooth
- Speakers and AUX output
- Microphone
- USB A and USB C ports
- Battery percentage
- HDMI
- Sleep / Wake-up
- Windows 10/11 in dual boot with synced time

## What doesn't works:
- HP IR/UVC Camera
- Hardware optimisation
- Third party apps

## Points to work on:
- Stability improvements (due to AMD compatibility problems)
- Camera fixes
- Hardware/Battery efficiency

## Screenshots:
![](./Screenshots/View.png)
![](./Screenshots/Geekbench_CPU.png)
![](./Screenshots/Geekbench_GPU.png)
![](./Screenshots/Battery.png)
![](./Screenshots/CPU_Usage.png)
![](./Screenshots/RAM_Usage.png)
![](./Screenshots/Disk_Usage.png)

## Acknowledgements
Thanks to the whole hackintosh community, to the Dortania OpenCore Install guide, and to [Nootred](https://chefkissinc.github.io/applehax/nootedred/) for enabling graphics acceleration on AMD.
