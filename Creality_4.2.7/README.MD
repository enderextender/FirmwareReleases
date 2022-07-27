Using a Creality Touch screen or Creality Color LCD (S1/V2), perhaps check out the "Professional Firmware" Project.  This alternative build of marlin allows you to set printer size options from the LCD and has several other advanced configuration and bed tramming features not contained in the base marlin builds.

https://github.com/mriscoc/Ender3V2S1/releases

Compiled for Creality 4.2.7 board.

ENDER EXTENDER IS NOT RESPONSIBLE FOR FIRMWARE ISSUES, AND DOES NOT WARRANTY THIS FIRMWARE TO BE USABLE FOR ANY PURPOSE.. USE AT YOUR OWN RISK.
ENDER EXTENDER DOES NOT PROVIDE SUPPORT FOR COMPILING OR USING FIRMWARE

Naming conventions used:

E<Size/Type>_CREALITY_427_<COLORLCD?>_<BLTOUCH?>_<ZMIN?>.bin
  If using color LCD (V2 style), the firmware will have COLORLCD in the name,
otherwise it will not.
  If using BLTOUCH, it will have BLTOUCH in the name.  If you have the BLTouch two pin connector connected to your ZMin port, use the one with ZMIN in the name.  

Example:
firmware_E400XL_CREALITY_427_COLORLCD_BLTOUCH_ZMIN.bin
- 400 XL for Creality 4.2.7 board with Color LCD and the BLTouch plugged into Zmin port.
For the LCD Screen on V2 printers you need to download the DWIN_SET.zip file and unzip it to an sdcard, remove the back of the lcd cover, and insert the sd card into the slot then power on your printer.  The screen will turn blue then orange/red, turn off the printer, remove the LCD and put the cover back on, etc.
