# hackentosh_wopr

# Hardware
Case: 
- Lian Li O11 Dynamic XL CPU:
- Intel Core i9-10900K 3.7 GHz 10-Core Processor
- GPU: Saphire Radeon 5700XT
- RAM: 128GB (4x32)G.Skill Trident Z RGB
- Motherboard: Gigabyte Z490 Vision D with 2x USB-C/Thunderbolt 3 ports
- Power Supply: EVGA P2 750 W 80+ Platinum Modular ATX Power Supply
- Drives: 2 x Sabrent Rocket 4.0 1 TB M.2-2280 NVME Solid State Drive: M2A: Windows/Linux; M2B: Mac OS Big Sur; Samsung 860 Evo 2 TB 2.5" Solid State Drive (for data storage)
- Audio Codec: Realtek ALC1220-VB
- Ethernet Card: 1Gbit Ethernet: Intel I219; 2.5Gbit Ethernet: Intel I225-V Wifi/BT Card: YOUBO PC Hackintosh WiFi Card BCM94360CD 802.11a/g/n/ac 1750Mbps BT4.0 PCIe Network Adapter
- SATA Expansion Card: Ziyituod PCIe SATA Card, 4 Port (using NvME slots A&B disables SATA ports 0, 4, 5)
- Keyboard: daskeyboard Das Keyboard - DASK4
- Mouse: Steelseries Riva 600
- Monitor: LG 27UK850 & LG32GN50T
- BIOS revision: Vision D7a 

# What is Working
- Tested with macOS Big Sur
- Wifi and Bluetooth (via B BCM94360CD using the YOUBO fenvi Wireless Card). IMPORTANT: Replacing the onboard Intel WiFi-card doesn't work. Tried this before reading SchmockLord’s guide and had to return it.
- Audio: Realtek ALC1220-VB
- USB, all ports (except the USB 2.0 on the rear panel labeled "BIOS". Disabled this due to the 15 port limit)
- Thunderbolt 3 including Hot-plug - Requires flashing the onboard chip
- 1Gbit Ethernet (Intel I219-V) 2.5Gbit Ethernet (Intel I225-V)
- With iMac20,2: SideCar and AppleTV, but no Amazon Prime Video and Netflix in Safari. But Amazon Prime and Netflix works with other browsers like Unlock with AppleWatch Shutdown Restart

# What is not Working
Sleep/Wake - Issue where computer goes to sleep but rewakes almost immediately
Amazon Prime Video and Netflix in Safari.

# Guides and Credits:
OpenCore Manual, Open Core Desktop Guide and tonymacx86 forum. Special thanks to SchmockLord and his Github guide for making this build so easy.

# To do:
Fix Sleep/Wake issue
Full-loop water cooling
DRM/Safari Netflix and Prime Video issues
