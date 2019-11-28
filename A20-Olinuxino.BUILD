# LibreElec.tv Build instructions for A20-OLinuXino-* boards
This repo is based on Jernej Škrabec work https://github.com/jernejsk

1. Getting sources
```bash
# https://github.com/OLIMEX/LibreELEC.tv -b olinuxino
# cd LibreELEC.tv
```
2. Build sources
```bash
#PROJECT=Allwinner DEVICE=A20 ARCH=arm UBOOT_SYSTEM=lime2 make image
```
3. Write Image to SD-Card
```bash
#cd target
#gunzip LibreELEC-A20.arm-*.img.gz
#dd if=LibreELEC-A20.arm-<date_hash>.img of=/dev/sdX 
```
