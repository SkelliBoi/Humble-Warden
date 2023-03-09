# Just a Humble Warden

The Just a Humble Warden modlist is my attempt to create a Dragon Age: Origins modlist using Wabbajack. If you don't know what Wabbajack is, you should check it out here: <https://www.wabbajack.org/#/>

The goal of this modlist is to create a version of the game that plays smoothly (without encountering any annoying bugs), has some graphical changes and improvements, and adds some changes to improve the quality of life. Basically, to create the ideal version of the game that I would like to play.

The modlist was made using the Steam version of Dragon Age: Origins - Ultimate Edition, and I can not guarantee any other version will work.

The installation of this mod list requires a total of about 61GB (this could likely be reduced in the fututre as I learn more of the features of Wabberjack). ~24GB for the base game, ~30GB for the modlist, and ~8GB for the downloads. The download itself should take about 20 minutes, depending on your internet speed.

## Install Dragon Age: Origins - Ultimate Edition

You will need a clean installation of the game.

1. First, uninstall the game from Steam. Make sure that your installation folder is completely empty. Delete any files still left in the install folder ("steamapps/common/Dragon Age Ultimate Edition").

2. Install Dragon Age: Origins - Ultimate Edition. You will need the most recent version of the game, with all of the DLC's available.

3. Run the game once, and choose "Configure". In the Video Settings, choose your settings (16:9, 1920x1080 recommended). 

4. Go to the main menu, check the "Other Campaigns" option, and exit. (If the "other campaigns" button is darkened, exit the game and navigate to "steamapps\common\Dragon Age Ultimate Edition\redist", and run "DAOU_UpdateAddinsXML_Steam.exe".)

## Install "Just a Humble Warden" via Wabbajack

Now, you must install the modlist using Wabbajack.

1. Download Wabbajack if you don't have it already, and place it inside its own folder.

2. Create another folder called "Just a Humble Warden" and place it next to the Wabbajack folder (NOT INSIDE!).

3. Open Wabbajack and click on "Browse Modlists" or "Install From Disk" depending on how you want to install it.

3. If using "Browse Modlists" search for "Just a Humble Warden" and click on the little down arrow to download the list, and once that's done, click on the play button. If using "Install From Disk" just select the file from your computer.

4. As the installation folder, choose the empty folder that was created in step 2.

5. Downloads will be auto-selected for you, but you can change that location if you want. 

6. Click the "play" button to install the modlist.

It's possible that at some point the installation will give an error. Often times just trying it again will solve the problem.

To check wether the installation was successful, look for the "ModOrganizer.exe" file inside the installation folder and open it. If it has a Dark theme, the installation should be a success.

## Install DAZIPs

Unfortunately, not everything can be done automatically using Wabbajack, so a few more steps are required.

1. Inside ModOrganizer, go to the dropdown list at the top right and select "DAUpdater". Then press the Run button next to it. This should launch "DAUpdater.exe".

2. Inside the program, choose "Select DAZIPs", and find the "DaZips" folder. It should automatically start there, but if it does not, look for the folder inside the modlist installation folder ("Just a Humble Warden\DaZips"). 

3. Select all of the files inside the folder. They should appear in DAUpdater.

4. Select all of the DAZIPs within DAUpdater, and choose "Install Selected".

5. Wait for all of them to read "installed". Afterwards, you can close the program.

For me it works if I select all files at once, but if it doesn't you might need to do it in steps.

## Merge CharGenMorphCFG files

Many mods come with a CharGenMorphCFG file, but the game can only use one. Therefore, these files need to be merged.

1. Inside ModOrganizer, go to the dropdown list at the top right and select "CharGenMorph Compiler". Then press the Run button next to it. This should launch "CharGenMorph Compiler".

2. It will ask what game you want to modify. Select Dragon Age: Origins.

3. The paths should already be set up, but just in case, make sure in the "Path Configuration" tab, the path under "Dragon Age Paths" is set to "..\mods".

4. Go to the compiler tab and click the compile button at the bottom of the screen. Wait for it to finish, it will give a pop-up.

5. On the References tab click the Remove Bad References button at the bottom of the screen. Once this is finished you can close the program.

6. Find the chargenmorphcfg.xml file inside the mods folder inside your installation folder ("Just a Humble Warden\mods\chargenmorphcfg.xml"). It should be the only loose file in there.

7. Move the file to "Just a Humble Warden\Stock Game\packages\core\override\". If the override folder doesn't exist yet, create it.

## Run FIX_DLC

This final step is just to run a fix for DLC items.

1. Inside ModOrganizer, go to the dropdown list at the top right and select "FIX_DLC". Then press the Run button next to it. This should open the command prompt.

2. It will ask you to press any button. Do so (spacebar is fine).

## Unlcok LAA for the .exe file

The .exe file for the base game isn't large address aware. The modlist should automatically replace the .exe file with a working one, but just in case it doesn't work, I would recommend using the following program <https://www.techpowerup.com/forums/threads/large-address-aware.112556/> to update the launcher ("Just a Humble Warden\Stock Game\bin_ship\daorigins.exe").

## Starting the game

Once all of the previous steps are done, go to the dropdown list at the top right and select "Dragon Age: Origins" to start the game. The game must always be run through here, not through Steam.

## Optional Mods

There are some optional mods that you can turn off if you don't want them (Skip the Fade, Skip Ostagar). Just uncheck the checkmark next to them to turn them off.
