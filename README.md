# Ender 3 Marlin Firmware for SKR 3 EZ
Ender 3 Marlin Firmware (v2.1.2.4 with pre-build and source) for SKR3 EZ

Source code and compiled firmware included!

I made this with other makers in mind, since I couldn't find any info on the internet about compiling and building a perfect version of the Ender 3 marlin firmware on a SKR 3 EZ specifically. 

TO USE PRE-BUILT FIRMWARE:
 - Make sure to format a micro-SD card Fat32 (Make sure to backup if you had previous files!)
 - Simply drag firmware.bin into micro-SD card (Make sure this is the root/starting directory, not a folder)
 - Put micro-SD card into Ender 3 and start it up!
 - You should see it working, but in case you're not sure by the LCD, if you check the micro-SD card again, the file name should now be firmware.cur (Make sure not to delete this!)

Drivers:
 - X: TMC2209 
 - Y: TMC2209 
 - Z: TMC2209 
 - E0: TMC2209 

If you feel like you get stuck (especially on the wiring of the limit switches), check out this playlist:
 - https://youtube.com/playlist?list=PLcx00jUOGPz3nLvPSTIJgr3uwRqoiYKw_&si=xIjnI_TO8GCccsnD

If you need help, feel free to make an issue that I can reply to!

Q&A:

Q: Is there BL Touch Support?
A: Yes! Make sure to enable it in your configuration. (I disabled it because my BL Touch was a knock-off, be weary of them! Research the wiring before purchasing!)

(More Q&A coming soon!)
