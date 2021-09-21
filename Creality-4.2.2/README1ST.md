Only for Creality 4.2.2 boards as found in Ender 3 V2, Ender Extender V2 400XL, 400x400x500

WARNING:  Creality boards can be sensitive to SD card variations in size and allocation bytes.  
Before you start, please make sure you format the SD card using Windows Explorer for FAT32, 4096 Allocation units, for a size of no more than 8 gigabytes.  
We've even had to repartition an SD card to 4 gigabytes (Using the Windows Disk Manager app) then format it to Fat32, 4096 allocation units.  In our test, the 
printer was showing a blue screen.

ENDER EXTENDER DOES NOT PROVIDE SUPPORT FOR COMPILING OR USING FIRMWARE

ENDER EXTENDER IS NOT RESPONSIBLE FOR FIRMWARE ISSUES, AND DOES NOT WARRANTY THIS FIRMWARE TO BE USABLE FOR ANY PURPOSE.. USE AT YOUR OWN RISK.

This firmware was compiled from Jyer's firmware github.  Many thanks to all his hard work.  This is a big improvement over stock!

You must update the LCD firmware!

Read the full instructions at github
https://github.com/Jyers/Marlin/tree/Ender_3_V2_Extensible_UI/Display%20firmware



Instructions:

You should have an original firmware.bin file so you can load it in case this blows up.

Step 1: Copy firmware*.bin to your sd card
Step 2: Copy folder DWIN_SET to your sd card
Step 3: Dismount and remove the back cover to your LCD display.
Step 4: Insert SD card into lcd display's sd port
Step 5: Turn on your printer, this will update the display
Step 6: Turn off the printer. Remove SD Card. Reassemble and remount the LCD display
Step 7: Insert SD card into printer.  
Step 8: Turn on printer
Step 9: Test

The file names indicate some portion of the configuration.

Specifically, bltouch has 5 pins, 3 for the servo, 2 for the trigger pin.  Some people like to use the Z endstop port on their board to connect the BLTouch.  This configuration is called bltouch-zmin.  If you're using a standard 5 pin bltouch connector, use bltouch-5pin-port.