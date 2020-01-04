DV-DS-CompatPacks1 ["Aetherius" - Compatiblity Patches for Various mapsets]

- Includes compatiability patches and PK3 files for the following wads/etc. Though keep in mind some of these are currently incomplete.
	- Going Down (loaded as a subfolder)
	- Hellbound (loaded as a subfolder)

HOW TO INSTALL / RUN / ETC:

 - Important - Make absolutely sure you got DV-DS-ComboPack [@ https://github.com/LordMisfit/DV-DS-ComboPack ] working right before you do anything here. Refer to that repository's README.md file for more information.

 - Installing 1 - Make sure you unzip the entire "DV-DS-CompatPacks1" folder inside the zip file to your designated GZDoom folder. Do not try to install the subfolders within into "DV-DS-ComboPacks1" or into your main GZDoom folder, or you've done flapped it up and have to do everything up to this point on both repositories over again. :V
 - TL;DR: So basically make sure "DV-DS-ComboPacks" & "DV-DS-CompatPacks1" are seperate subfolders in your main GZDoom folder. :P

 - Running - 1. There is no launcher packed for use with DV-DS-CompatPacks1, you'll have to rely on command lines for now. My general method is to create a batch [.bat] file and name it something you'll remember. Remember you can right click a .bat file and "edit" them to change the command line used inside.

 - Running - 2. To run Going Down w/ "Aetherius" Command line: "start gzdoom.exe -iwad doom2.wad -file "DV-DS-ComboPack" "DV-DS-CompatPacks1/GoingDown" +hud_scale 0 exit" 

 - Running - 3. To run Hellbound w/ "Aetherius" Command line: "start gzdoom.exe -iwad doom2.wad -file "DV-DS-ComboPack" "DV-DS-CompatPacks1/Hellbound" +hud_scale 0 exit" 
 - Note: If you want higher-resolution music, add "DV-DS-CompatPacks1/hellbnd-HMUS.wad" after the Hellbound folder in the command line.
