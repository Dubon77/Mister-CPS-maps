# Mister-CPS2-maps
Arcade stick mappings for tournament play of Mister FPGA cps2 core


The aim of these files are to provide Mister users with arcade stick map files in order to streamline the mappingprocess at tournaments.    
putting these files in an empty /media/fat/config/inputs/ folder should result in any supported stick to work for any cps2 6-button game.
The advantage of this aproach is that you only need to map once for Mister's main menu, and you shouldnt have to touch the in cps2 core mapping, and so pause also cant be mapped.

sticks currently added are: 
brook Universal fighting board ps4 mode (latest fw)
Hori hrap N (ps4 mode)
Hori fighting edge ps4 (ps4 mode)
Madcatz te-s+ (ps4 mode)
Madcatz sfiv TE (360)
mpadcatz ssfiv TE-S (360)


to use test these files, navigate to the config/inputs folder on your SD card, backup the .map files that that are there, then delete them and copy these .map files the the empty config/inputs folder. 

If you want to contribute to add to thirepo please follow these exact instructions to map your stick in the same way:

first make sure your stick is set to digital pad mode 

then press the reset button on your mister to reboot to main menu.
then hold down the user button on your Mister for 3 seconds to bring up the controller map wizard.
First thing that will pop up is:
DPAD Test: Press right -> press right on your stick
Stick 1 test: Tilt right -> short press the userbutton on your Mister to skip
Stick 2 test: Tilt right -> short press the userbutton on your Mister to skip
now the virtual snes pad will show:
R -> press right 
L -> press left
D -> press down
U -> press Up
A -> press LK
B -> press HP
X -> press MP
Y -> press LP
L -> press MK
R -> press HK
select -> press start/options (yes i know)
start -> press select 
mouse move right -> short press the userbutton on your Mister to skip
mouse move left -> short press the userbutton on your Mister to skip
mouse move down -> short press the userbutton on your Mister to skip
mouse move up -> short press the userbutton on your Mister to skip
mouse btn left -> short press the userbutton on your Mister to skip
mouse btn right -> short press the userbutton on your Mister to skip
mouse btn middle -> short press the userbutton on your Mister to skip
mouse emu/sniper -> short press the userbutton on your Mister to skip
Menu -> press Home/Guide
Menu:OK -> press LK
Menu:Back -> press MK
stick 1:tilt right -> short press the userbutton on your Mister to skip
stick right:tilt Down -> short press the userbutton on your Mister to skip

That should be it. now navigate to your inputs folder and find the map file that was just generated (you should be able to tell witch it is from the Time and date it was modified) and send me a copy so i can add it to this repo. 
