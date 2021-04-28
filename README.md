# FirmwareReleases
These are miscellaneous firmware files compiled for the Ender Extender kits.  

Files for popular types of control boards are available in each folder.  Most will have bltouch and nonbltouch versions.

NOTE

ENDER EXTENDER DOES NOT WARRANTY THESE FILES TO BE FREE FROM DEFECTS
ENDER EXTENDER DOES NOT PROVIDE SUPPORT FOR COMPILING OR USING FIRMWARE


3D Printer enthusiasts should strive to attain the skills necessary to build their own working firmware.

This is a Do It Yourself hobby and sometimes that is what you need to do.  Please consult Youtube or Google
for tutorials on how to install the compiler software, make changes to the code, and upload the files to your control board.

We have only provided .bin files that work with 32 bit boards.  Uploading firmware to 8 bit stock boards requires additional tools and skills.  
We believe that upgrading from the 8 bit stock boards is the best course of action.

Each manufacturer creates a different set of rules for firmware.bin file naming conventions

Bigtreetech
File should be named firmware.bin
Download your desired file, rename it to firmware.bin and copy it to an SD card.

Creality

The Creality 4.2.2 and 4.2.7 boards require firmware.bin to be named firmware-xxxxxx.bin where xxxxxx is sum number.  
You can't use the same number twice in a row, thus, if you use firmware-1234.bin and download an updated version, 
you need to change the name to firmware-12345.bin or something that is not the same as the last file you used.

