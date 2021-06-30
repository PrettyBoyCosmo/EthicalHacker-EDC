# Building an Ethical Hacker Every Day Carry [EDC]
> Created by : Chris Taylor [Blue Cosmo]

## Resources:
- YouTube - https://www.youtube.com/c/CosmodiumCS
- Part 1 - https://www.youtube.com/watch?v=j0v0rJsWDdE 
- Part 2 - https://youtu.be/ao32BS8fwaM

## Part 1 | Overview
```
in this part, we discussed what tools we will [probably] use for this project.
```
Here is the list:
- USB RubberDucky
- Shark Jack
- Bash Bunny
- USB A - Micro USB adapter
- USB A - USB C adapter
- USB C - USB A adapter
- Custom Malware Drive
- Parrot Security OS bootable drive
- TP Link - Wireless Network Adapter
- Micro SD Card adapter
- 64GB USB Drive
- 2200mAh Portable Charger
- USB C - USB A cord
- USB Ethernet Adapter Stickers
- Hak5 Information Cards
- KNIFE PEN!!!
- Screw Driver 
  - SIM Bit
  - 0.8 Bit [I-PHONE]
  - 1.2 Bit [MACBOOK]
  - PZ0 Bit [WINDOWS]

## Part 2 | USB RubberDucky Wifi Exfiltration
```
in this part, we built a payload for exfiltrating wifi passwords from Windows 10 coputers
all code for this project is in the 'usbrd-wifi' directory
```
- we took 'inspiration' from a script developed by 'brain eater'
- in our modifications we:
  - allowed twinduck functionality
  - allowed for different file names for each computer we interact with
    - this lets us 'backup' multiple wifi passwords from multiple computers without overwriting the file
- we then flashed the 'twinduck' firmware on to our USB RubberDucky
---
Links:
- Unmodefied Script - https://forums.hak5.org/topic/40442-help-with-wifi-password-grabber/
- DuckyFlasher - https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Flashing-ducky 
- USB RubberDucky Tutorial - https://www.youtube.com/watch?v=o1RbXtx0r4U 
