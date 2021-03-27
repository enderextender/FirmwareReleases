Only for Creality 4.2.2 boards as found in Ender 3 V2, Ender Extender V2 400XL, 400x400x500

You could also use this on a 400x400x250 Ender Extender.  Just be aware it won't stop going up at 250 if you tell it to higher :)

There are two bin files in this directory

firmware-20210319-135747-IIC_BL24CXX_EEPROM.bin
firmware-20210319-135837-SDCARD_EEPROM_EMULATION.bin

On our test system, Creality 4.2.2 board in V2 the firmware firmware-20210319-135747-IIC_BL24CXX_EEPROM.bin
works but the mesh from auto levelling is not used when printing, thus it's unknown where 
the system is saving the mesh when you use store settings.  I can't get a straight answer from Marlin devs
so I am providing two versions.  

The SD Card emulation firmware writes an EEPROM.DAT file to the SD Card, this is where the mesh data is stored when Marlin does not detect an Eeprom chip on the control board. Actually this was the default from factory for Creality.

When we print a test file with the sd card emulation, the auto level mesh data is used and the tilt of the bed is compensated.  When we use the IIC version, it is not.  So your mileage may vary.  Try both and do a test print.

Also, we have enabled Restore mesh after G28, so you do not really need M420 S1 in your gcode unless you want to customize it, like having it fade the compensation out after specific Z height (M420 S1 Z2 ...)

Always store settings (Control menu) after using Auto Level, as it does not automatically save the mesh data.

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