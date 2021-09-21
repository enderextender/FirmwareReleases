Compiled for Creality 4.2.7 board.

WARNING:  Creality boards can be sensitive to SD card variations in size and allocation bytes.  
Before you start, please make sure you format the SD card using Windows Explorer for FAT32, 4096 Allocation units, for a size of no more than 8 gigabytes.  
We've even had to repartition an SD card to 4 gigabytes (Using the Windows Disk Manager app) then format it to Fat32, 4096 allocation units.  In our test, the 
printer was showing a blue screen.

ENDER EXTENDER IS NOT RESPONSIBLE FOR FIRMWARE ISSUES, AND DOES NOT WARRANTY THIS FIRMWARE TO BE USABLE FOR ANY PURPOSE.. USE AT YOUR OWN RISK.
ENDER EXTENDER DOES NOT PROVIDE SUPPORT FOR COMPILING OR USING FIRMWARE

Bltouch variants use the BLTouch 5 pin connected to BLTouch port

For printers without BLTouch, use the nobltouch equivelant file

FOR THE ENDER 3 MAX, skip the lcd portion

For the V2 with the color LCD non touch screen, you must also update the LCD.  Others can skip this.

Unmount the lcd
Remove back cover
Insert SD card with contents of DWINSET folder in the root
Reconnect LCD
Turn on printer
LCD will update new firmware
Disconnect, reassemble, and remount LCD