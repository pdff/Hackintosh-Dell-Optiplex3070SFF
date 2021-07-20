# Hackintosh-Dell-3070-SFF-MacOS11.4-OPENCORE
Dell OptiPlex 3070 with i5-9600k working EFI on BigSur 11.4


Hardware Specs

Desktop Computer: Dell OptiPlex 3070 Small Form Factor

CPU: Intel® Core™ i5-9600k

iGPU: Intel® UHD Graphics 630

RAM: 32gb DDR4 2400mhz

HDD: Samsung EVO 970 NVMe SSD 256gb

Working: 
CPU Turbo Boost & Thermal ThrottlingALC 255 audio

All USB Ports

LAN

Wi-Fi & Bluetooth Working flawless thanks to openintelwireless!

Airdrop & Airplay

Sleep

Internal sound and hdmi

Not working: 

Display sleep (thinks it's an external monitor)  


BIOS Settings

General → Advanced Boot Options: uncheck
System Configuration → SATA Operation: AHCI
Secure Boot → Secure Boot Enable: Disabled
Intel® Software Guard Extensions™ → Intel® SGX™ Enable: Disabled
Power Management → Block Sleep: check
Virtualization Support → VT for Direct I/O: uncheck
BIOS Settings via GRUB (Optional)

Set Pre-Allocated DVMT to 64M: setup_var 0x8DC 0x02
Disable CFG lock: setup_var 0x5BE 0x00
