# Surface Pro 4 & Surface Book (gen1) Hackintosh
This provides the ability to boot the Surface Pro 4 &amp; Surface Book (gen1) to macOS as a hackintosh. This may also work on the Surface Pro 5 &amp; 6 as well as newer Surface Book generations with some minor modifications. 

EFI supports macOS version 10.15.x and above. Not all features may work on all versions of macOS

OC version 0.8.3

Star or watch this github repository to be notified of updates coming soon. 

If you see anything that could be added or changed don't hesitate to sumbit a request.


## *** NOTICE ***
### Do not update kexts labeled as "custom" manually if they exist, instead wait for an update. 
### Touch is Technically supported in the posted EFI files however it requires [@Xiashangning's IPTSDaemon](https://github.com/Xiashangning/IPTSDaemon) in order to work. Keep in mind that at the moment IPTSDaemon won't work until it is updated for "FMT 9.0.0". Until FMT is updated touch will not work.

## Supported Surface Specifications:

| Model: | Pro 4 | Book (gen1) |
|---|----------|----------|
|CPU| 6th Gen: i3, i5, i7 | 6th Gen: i3, i5, i7|
|GPU| Iris 520 | Intel Iris 520 / Nvidia GPU (unsupported) |
|RAM| 4/8/16 GB | 4/8/16 GB |
|SSD| 128GB/256GB/512GB/1TBs NVME | 128GB/256GB/512GB/1TB NVME |
|WiFi| Unsupported | Unsupported |
|Batt| XX,000 mAH | XX,000 mAH |
|USB| 1x USB 3.0 | 2x USB 3.0 |




## Instruction Guides

### [Chapter 1) Quick Start Install]
### [Chapter 2) BootCamp Install]
### [Chapter 3) Quirks & Fixes]
### [Chapter 4) Additional Drivers]
### [Chapter 5) Booting Other OS's with OpenCore]
### [Chapter 6) Other Operating Systems]
### [Chapter 7) Other OS Quirks & Fixes]
### [Chapter 8) Windows 11 Upgrade and/or Clean Install]


## What works 

- macOS 10.15.x and above
- Fan
- USB
- Battery
- Trackpad
- TouchScreen (Requires IPTSDaemon, see link in "notes")
- Keyboard (may not turn back on after opening keyboard from sleep)
- Audio
- Recovery
- Brightness Keys
- Power Management
- Sleep / Wake




## What doesn't work

- SDcard
- Wi-Fi (unsupported Chipset)
- Bluetooth (unsupported Chipset)
- FileVault
- Windows Boot Support From OpenCore Bootloader
- Accelerometer (unsupported device)


## Credits
Special thanks to [@Xiashangning](https://github.com/Xiashangning) for the excellent work done on his BigSurface kext<br>

