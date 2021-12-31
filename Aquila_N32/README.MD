Compiled for Voxelab Aquila N32 board.

ENDER EXTENDER IS NOT RESPONSIBLE FOR FIRMWARE ISSUES, AND DOES NOT WARRANTY THIS FIRMWARE TO BE USABLE FOR ANY PURPOSE.. USE AT YOUR OWN RISK.
ENDER EXTENDER DOES NOT PROVIDE SUPPORT FOR COMPILING OR USING FIRMWARE

Naming conventions used:

firmware_E<Size/Type>_AQUILA_N32_<BLTOUCH?>_<ZMIN?>.bin
  If using BLTOUCH, it will have BLTOUCH in the name.  If you have the BLTouch two pin connector connected to your ZMin port, use the one with ZMIN in the name.  

Place the firmware*.bin file in to a folder called firmware on your sd card.  Insert into the printer, turn off then turn on the printer.  Update will proceed.

Example:
firmware_E400XL_AQUILA_N32_BLTOUCH_ZMIN.bin

- 400 XL for N32 board and the BLTouch plugged into Zmin port.

Updating the DISPLAY is also required.

You need to download the DWIN_SET.zip file and unzip it to an sdcard, remove the back of the lcd cover, and insert the sd card into the slot then power on your printer.  The screen will turn blue then orange/red, turn off the printer, remove the LCD and put the cover back on, etc.

After you have prepped the sd card you should have folders like so

DWIN_SET
-- inside here a bunch of files from the dwin_set.zip
firmware
-- inside here a file named firmware*.bin

