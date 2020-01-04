# Hackintosh
Files and info relating to my hackintosh build

<img src="neofetch.png" width="800" />

Reddit build thread: https://www.reddit.com/r/hackintosh/comments/dy4zcp/another_i99900kz390_designare5700xt_success_story/

* Intel Core i9-9900K CPU
* Corsair H100x CPU cooler
* Gigabyte Z390 Designare motherboard
* Corsair Vengeance LPX 32 GB DDR4-3000 memory
* Samsung 970 Evo Plus 500 GB M.2-2280 NVME SSD (macOS)
* Samsung 970 Evo Plus 1 TB M.2-2280 NVME SSD (macOS user profile)
* Samsung 860 Evo 1 TB 2.5" SSD (Windows 10)
* PowerColor Radeon RX 5700 XT 8 GB Red Devil GPU
* Silverstone Strider Titanium 800 W 80+ Titanium PSU
* Fenvi FV-HB1200 Wifi/Bluetooth PCIe card
* Dell P2415Q 23.8" 4k monitor (x3)
* Logitech MX Keys keyboard
* Logitech G502 Lightspeed mouse
* Noctua fans
* Apple Mac G5 case (free) with Laser Hive conversion parts

Full build images here, including all the case modification work: https://imgur.com/gallery/evzOYV9


Please note - EFI is just for reference, kexts etc. may not be current.

## Update 2020-01-04
Replaced the failing Broadcom BCM94360CS2 WiFi/BT PCIe adapter with a Fenvi FV-HB1200. Works perfectly right out of the box. 

## Update 2019-12-27
All of a sudden I had the dreaded 'Couldn’t allocate runtime area' boot error, after months of trouble free hackintoshing. Despite a variety of slide values calculated from a memmap output, nothing seemed to work. I tried disabling a few things in the BIOS (LED lighting, USB legacy support, etc) but nothing fixed it. I finally disabled the iGPU and the system booted fine again. Owing to that, I've now changed to iMacPro1,1 SMBIOS and all seems well again - power management looks to be fine, previews work great and us the dGPU, as does video encoding, Premiere Pro, etc. I updated Clover and some kexts that had updates too before upgrading to macOS 10.15.2 which is running great so far...