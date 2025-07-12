# Hackintosh for Asrock B460M-ITX/AC

The EFI for Asrock B460M-ITX/AC supporting macOS Sequoia. 

I update this EFI based on @fzlee 's work to make it supports the latest macOS 15.5. 

## Updates

Opencore 1.0.5

Multiple kexts have been updated to latest version

AMFIPass.kext has been added and `amfi=0x80` has been removed

![](https://raw.githubusercontent.com/jzmrexu1s/B460M-ITX-AC-EFI-SEQUOIA/refs/heads/master/images/sequoia-15.5.png)

## Hardware

- Asrock B460m-ITX/AC
- Intel Core i5-10600KF
- Sapphire RX 570 4GB
- Kingston HyperX 3200MHz 16GB * 2
- Samsung SSD 990 PRO 4TB
- Broadcom BCM94360CS2

## Update to Sequoia from Sonoma with OCLP installed

1. Update Opencore Legacy Patcher to latest version. 
2. Update EFI. 
3. Create macOS Installer in Opencore Legacy Patcher. 
4. Install macOS Sequoia. 
5. Clear NVRAM. 
6. Execute Post-Install Root Patch in Opencore Legacy Patcher. 
7. Restart. 
8. Now both Wi-Fi and bluetooth should work. 