# Mister-CPS2-maps
Arcade stick mappings for tournament play of Mister FPGA cps2 core


The aim of these files are to provide Mister users with arcade stick map files in order to streamline the mapping process at tournaments.    
putting these files in an empty /media/fat/config/inputs/ folder should result in any supported stick to work for any cps2 6-button game.

The advantage of this aproach is that you only need to map once for Mister's main menu, and you shouldnt have to touch the in cps2 core mapping, and so pause also can't be mapped.

sticks currently added are: 

Brook Universal Fighting Board ps4 mode (latest fw),

Brook PS4 Fighting Board Plus ps4 mode (fw v2.3, 6-2022),

PS360+ (fw 1.65)

Hori HRAP N (ps4 mode),

Hori Fighting Edge ps4 (ps4 mode),

Hori VLX "kuro" ps4 (ps4 mode)

Hori VLX ex 360

Hori VLX "diamond" ps3

Madcatz TE-S+ (ps4 mode),

Madcatz SFIV TE (360),

Madcatz SSFIV TE-S (360).



to use/test these files, navigate to the config/inputs folder on your SD card, backup the .map files that that are there, then delete them and copy these .map files the the empty config/inputs folder. 

If you want to contribute to add to this repo please follow these exact instructions to map your stick in the same way:

first make sure your stick is set to digital pad mode 

then press the reset button on your mister to reboot to main menu.
then hold down the user button on your Mister for 3 seconds to bring up the controller map wizard.
First thing that will pop up is:

DPAD Test: Press right -> press right on your stick.

Stick 1 test: Tilt right -> short press the userbutton on your Mister to skip.

Stick 2 test: Tilt right -> short press the userbutton on your Mister to skip.

now the virtual snes pad will show:

R -> press right.

L -> press left.

D -> press down.

U -> press Up.

A -> press LK | cross  |A.

B -> press HP |R1      |RB.

X -> press MP |triangle|Y.

Y -> press LP |square  |X.

L -> press MK |circle  |B.

R -> press HK |R2      |RT.

select -> press start/options/menu (yes i know this is counter intuitive but its related to the way the cps2 core maps to the virtual snes pad).

start -> press select/share/back/view

mouse move right -> short press the userbutton on your Mister to skip.

mouse move left -> short press the userbutton on your Mister to skip.

mouse move down -> short press the userbutton on your Mister to skip.

mouse move up -> short press the userbutton on your Mister to skip.

mouse btn left -> short press the userbutton on your Mister to skip.

mouse btn right -> short press the userbutton on your Mister to skip.

mouse btn middle -> short press the userbutton on your Mister to skip.

mouse emu/sniper -> short press the userbutton on your Mister to skip.

Menu -> press Home/PS/XB/xGuide.

Menu:OK -> press LK | cross  |A.

Menu:Back -> press MK |circle  |B.

stick 1:tilt right -> short press the userbutton on your Mister to skip.

stick 1:tilt Down -> short press the userbutton on your Mister to skip.

That should be it. Now navigate to your inputs folder and find the map file that was just generated (you should be able to tell witch it is from the Time and date it was modified) and send me a copy so i can add it to this repo. You can mail it to me at simonvandenbon@gmail.com, you can send it to me over discord or you can make a PR here. please specify for witch stick (and what mode it was in) the map file is for.

Note: if the author of the cps2 core changes the mapping in the mra files, then these map files will need to be updated. because of this its probably a good idea to test if they are still correct before a tounament, after a misterupdate that affects the cps2 mra files.
Because the default mapping in cps1 mra files is not the same as for cos2, these maps will only be plug and play for cps2 games. for cps1 games you will still need to remap currently.

Note 2: some retail arcade sticks received revisions of their pcb. in those cases a map file for each revision will most likely be required.
