# Just a Humble Warden

The Just a Humble Warden modlist is my attempt to create a Dragon Age: Origins modlist using Wabbajack. If you don't know what Wabbajack is, you should check it out here: <https://www.wabbajack.org/#/>

For any support and suggestions, join the Discord here: <https://discord.gg/UkWFY6QEue>

The goal of this modlist is to create a complete, bug-free experience with graphical improvements, quality of life changes, and fixed contuinity errors. The real Ultimate Edition.

The installation of this mod list requires a total of about 68GB. ~24GB for the base game, ~23GB for the modlist, and ~21GB for the downloads. When playing with this modlist you must start a New Game. Continuing on an old save will cause issues and bugs.

Note that the modlist is still in its beta state and might contain bugs. It is constantly being worked on.

## Important Mods

Here I will note some important mods that change the Gameplay, that you should know how to use when you play:

* Extra Dog Slot - You will receive an item in your inventory called "Dog Whistle". Use this to call your Dog as an extra companion to your party. (Note that this mod could potentially have some issues with certain quests. If you can't move to somewhere on your map, remove the Dog from your party and try again.)
* Lock Bash - If you don't have anyone in the party who can pick a specific lock, your character will try to bash the lock instead. Items could get lost when breaking a chest. If you do have a party member who can unlock a chest or door, they will automatically do so.
* No Helmet Hack - Each party member will receive a helmet rulebook in their inventory. You can use this item to switch whether you want their helmet to be visible or not in-game.
* Base Chest - There is now a storage chest in your party camp to store items in.
* Respecification - This mod provides skills for each character to respec the six primary attributes as well as the classes and abilities. The skills for this can be found with the character's other skills.
* Advanced Tactics - Allows for more advanced tactics options, and adds a skill for your controlled character to be controlled for you, like your party members.
* Dragon Age Reborn - This mod changes a lot of the abilities in the game, so they are different from the vanilla game you might remember.

## Install Dragon Age: Origins - Ultimate Edition

You will need a clean installation of the game.

1. First, uninstall the game from Steam. Make sure that your installation folder is completely empty. Delete any files still left in the install folder ("Steam/steamapps/common/Dragon Age Ultimate Edition"). Also delete any files inside your documents folder for the game (Documents/BioWare/Dragon Age/). SAVE THE CURRENT FILES IN THERE SOMEWHERE ELSE AS A BACKUP IF YOU DON'T WANT TO LOSE THOSE SAVES!

2. Install Dragon Age: Origins - Ultimate Edition. You will need the most recent version of the game, with all of the DLC's available.

3. Run the game once, and choose "Configure". In the Video Settings, choose your settings (16:9, 1920x1080 recommended). 

4. Go to the main menu, check the "Other Campaigns" option, and exit. (If the "other campaigns" button is darkened or doesn't include all DLCs, exit the game and navigate to "Steam/steamapps/common/Dragon Age Ultimate Edition/redist", and run "DAOU_UpdateAddinsXML_Steam.exe".)

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

2. Inside the program, choose "Select DAZIPs", and find the "DaZips" folder. It should automatically start there, but if it does not, look for the folder inside the modlist installation folder ("Just a Humble Warden/DaZips"). 

3. Select all of the files inside the folder. They should appear in DAUpdater.

4. Select all of the DAZIPs within DAUpdater, and choose "Install Selected".

5. Wait for all of them to read "installed". Afterwards, you can close the program.

For me it works if I select all files at once, but if it doesn't you might need to do it in steps.

## Run FIX_DLC

This final step is just to run a fix for DLC items.

1. Inside ModOrganizer, go to the dropdown list at the top right and select "FIX_DLC". Then press the Run button next to it. This should open the command prompt.

2. It will ask you to press any button. Do so (spacebar is fine).

## Move Files from "Game Folder Files"

There are some files in the folder called "Game Folder Files" that you need to move to the location of your game installation. Just copy everything inside the folder and place it in your game installation folder (Steam/steamapps/common/Dragon Age Ultimate Edition/). If it asks to overwrite click YES. Make especially sure that the DAOrigins.exe gets replaced.

## Move Files from "Cutscenes 30fps" or "Cutscenes 60fps"

You have the option of upgrading the cutscenes in the game to 1080p with either 30fps or 60fps. Obviously the 60fps cutscenes are of better quality but for some players the 60fps cutscenes play in slow-motion in which case you should use the 30fps versions.

For the installation of the cutscenes just copy everything inside the folder and place it in your game installation folder (Steam/steamapps/common/Dragon Age Ultimate Edition/). If it asks to overwrite click YES.

## Optional Reshade

The installation comes included with SweetFX Reshade presets. This is a relatively old version of Reshade but is still pretty decent. In-game you can switch the Reshade on and off using the "SCROLL LOCK" button on your keyboard. So, if you don't want Reshade, you can just turn it off that way. 

If you do like Reshade, I would recommend upgrading the Reshade installation to a newer version. You will have to install version 3.4.0 manually in the following way:

1. Download Reshade 3.4.0 from the following link: https://www.mediafire.com/file/nbpgtocu66s5et6/ReShade_Setup_3.4.0.exe/file

2. Launch it and click on Select Game.

3. Navigate to the launcher ("Steam/steamapps/common/Dragon Age Ultimate Edition/Stock Game/bin_ship/DAOrigins.exe").

4. Select the Direct3D 9 option. Once it is finished you can close it.

In this version of Reshade you can open the menu using "shift + F2" and turn the effects on or off there.

You can of course also install the newest version of Reshade and use your own presets, but that's up to you.

Reshade can be quite demanding so if the game starts lagging, I would recommend turning it off.

## Starting the game

Once all of the previous steps are done, go to the dropdown list at the top right and select "Dragon Age: Origins" to start the game. The game must always be run through here, not through Steam.

Make sure to start a new game if you're playing this modlist for the first time.

While playing I recommend saving a lot! I can not guarantee crashes won't happen.

## Optional Mods

There are some optional mods that you can turn off if you don't want them (Skip the Fade, Faster Movement, etc). Just uncheck the checkmark next to them to turn them off.
