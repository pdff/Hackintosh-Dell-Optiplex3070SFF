Dell OptiPlex 3070 with i5-9600k on macOS Monterey 12.0
============================================

- Bootloader version: Opencore 0.7.1
- macOS version: macOS Monterey 12.0 (21A5284e)
![Oops!There was supposed to be an image here](https://i.imgur.com/nMixsSI.png)

#### Hardware Specification
| Component | Specs |
|------------|----------------------------------------|
| **CPU**     | `Intel® Core™ i5-9600k` |   
| **RAM**     | `32gb DDR4 2400MHZ`|   
| **HDD**     | `Samsung EVO 970 NVMe SSD 256GB`|
| **iGPU**    | `Intel® UHD Graphics 630`|
| **Audio**   | `RRealtek ALC3234`|
| **OS**      | `macOS Monterey 12.0 (21A5284e)`|
| **Boot**    | `OpenCore 0.7.1`|


#### Working: 

CPU Turbo Boost & Thermal Throttling
Audio
GPU 
All USB Ports
LAN
Airdrop & Airplay
Sleep
Internal sound and hdmi

Not working: 

Display sleep (thinks it's an external monitor)  

#### BIOS Settings

General → Advanced Boot Options: uncheck
System Configuration → SATA Operation: AHCI
Secure Boot → Secure Boot Enable: Disabled
Intel® Software Guard Extensions™ → Intel® SGX™ Enable: Disabled
Power Management → Block Sleep: check
Virtualization Support → VT for Direct I/O: uncheck

##### BIOS Settings via GRUB (Optional)

Set Pre-Allocated DVMT to 64M: setup_var 0x8DC 0x02
Disable CFG lock: setup_var 0x5BE 0x00
