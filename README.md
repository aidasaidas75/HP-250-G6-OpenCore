# HP-250-G6-BigSur-OpenCore-EFI


<p align="center">
 OpenCore 0.6.3 EFI folder for macOS BigSur Hackintosh (i3 6006u variant) 250 G6 HP Laptop
<img src="https://i.imgur.com/C5WJG3W.png" alt="look">
</p>

## What Works:
```
Audio
Battery Indicator
USB ports
Video Accelariton (1536 Mb Vram)
Wifi  (Swapped the original with macOS compatable DW1820(BCM4350) 802.11ac Wireless , if you have intel read What doesnt work! )

```
## What doesn't work:
```
Touchpad/Keyboard
Ethernet
Sleep
Intel Wifi (Search on github for a alt kext for intel wifi cards https://github.com/OpenIntelWireless/itlwm/releases)
Brightness
```

## TO DO:
```
*fix SMBIOS
*REMOVE SMC Light Sensor
*Remove other Kexts for touchpad/keyboard
*fix Sleep
*Remove DSDT.aml
lots more 
```

## Thanks to:
```
*Apple for their proprietery OS
*OpenCore devs and OpenCore Guides
*itlwm for the Wifi Intel driver port from Linux
*me Stefan
*others too :P
```
