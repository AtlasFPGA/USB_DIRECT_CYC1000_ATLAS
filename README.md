# USB_DIRECT_CYC1000_ATLAS
The CYC1000 and MAX1000 both has a selectable 2 pins with pull up and pull down.
![CYC1000](https://github.com/AtlasFPGA/USB_DIRECT_CYC1000_ATLAS/blob/main/cyc1000_VHDPlus.png)

Can be seen in CYC1000 the pull programable with a 4k7ohm "up or down" that is selectable in pins K1 & L1.

![MAX1000](https://github.com/AtlasFPGA/USB_DIRECT_CYC1000_ATLAS/blob/main/max1000_VHDPlus.png)

Can be seen in MAX1000 the pull programable with a 4k7ohm "up or down" that is selectable in pins B11 & G13.

There are cores in the future that uses a usb-keyboard using a Logitech Unifiing wirelles technologie.


Selected both pins In pull down -> USB-DIRECT

Selected both pins  In pull up -> PS2

The core we use for direct boot keyboard is:
https://github.com/TheSonders/USBKeyboard
