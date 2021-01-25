# Hackintosh-Asus-z10pe-d8-ws

Hi everyone,

I have successfully `booted` MacOS BigSur 11.1 on a ASUS Z10pe D8 WS.

You can find my EFI folder in this repository.

**OpenCore 0.6.5**

# Hardware

`Motherboard`: ASUS Z10PE-D8_WS

`CPUs`: Intel® Xeon® Processor E5-2683 v4 40M Cache, 2.10 GHz x 2

`GPU`: AMD Radeon RT 5700 XT 50th Anniversary

`Disk`: Samsung SSD 970 EVO Plus 1TB NVMe M.2

# Notice

## 1. This EFI not suitable for installation.

I got a reboot loop at install progress (about 20%).

The solution was I used is install the OS on other device and clone the disk to my 970EVO.

## 2. Regenerate System Serial Number & System UUID.

I have filled them with `aaaaaaa`, you should re-generate with OCC.

## 3. Logging

For testing, I set allow OC to write the log file to ESP.

Do not forget to set to your prefer at Misc -> Debug -> Target

# Known issues

- [x] The MVMe is an external disk (fixed with Innie.kext)
- [ ] Unknown processor

# Credits

Thanks for your support :) Your help was crucial for my build.

- [MaLd0n](https://www.olarila.com/topic/5676-folders-for-all-chipsets-clover-and-opencore) for OpenCore EFI folder example
- [Asher](https://github.com/Asher-/hackintosh-asus-z10pe-d8-ws) for a config.plist example
- [DalianSky](https://blog.daliansky.net/) for a easy USB boot image
- [Acidanthera](https://github.com/acidanthera) for too many things to mention each
- [RehabMan](https://github.com/RehabMan) for too many things to mention each
- [OpenCore project](https://github.com/OpenCorePkg) for this great bootloader
