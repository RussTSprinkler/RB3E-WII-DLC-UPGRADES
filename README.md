# RB3E-WII-DLC

This is a repository of DLC and Exports, converted to work in Rock Band 3 Enhanced for the Wii.
All songs are pre-packaged with upgrades from the Rock Band Harmonies Project, RB3PLUS, and RB4PLUS when applicable.

The goal of this repo is to make Wii/Dolphin more accessible, and to allow songs to be in an open-folder structure for simple adding editing and upgrading.

# INSTALLATION

***DOLPHIN***

This will only include instructions for VirtualSDCardMaker and ImDisk.

Download both programs from these links [HERE](https://www.mediafire.com/download/cfr9q8542e9lsos/Virtual+SD+Card+Maker.zip) and
[HERE](http://www.ltr-data.se/opencode.html/#ImDisk). 

A more indepth guide on these two programs if you need it is [HERE](https://dolphin-emu.org/docs/guides/virtual-sd-card-guide/).

Create an SD.RAW file using the VirtualSDCardMaker tool. I would recommend either 64 gigs or 32 gigs, depending on how many extra songs you would like. You may put this file wherever, but it would be a good idea to keep it in your Dolphin folder.
Using IMDisk, right click on your SD.RAW and mount it. A popup should occur, or a new icon will be placed on your taskbar. Hit yes. Then, make sure you select "Virtual disk drive accesses image file directly" and hit OK. You should now able to view its contents and edit them. Install RB3E to this folder. Inside the /apps/ folder, please copy the RB3Enhanced folder somewhere inside your Dolphin's directory.

Copy the songs you have downloaded with the RB3 folder on the root of your newly mounted SD.RAW file.
To double check and make sure you did it correctly, you should now see a (songs) and (lava) folder inside your RB3 folder.
Please open up [LavaManager](https://github.com/InvoxiPlayGames/LavaManager) at this point. It should automatically find your SD Card. Just hit "Load SD Card".
You should see your downloaded songs appear. Please hit Reload Song Files and then Finalize.

At this point, click the Config button within Dolphin. Go over to the Wii tab. Set your SD Card path to where you had placed your SD.RAW.
Please make sure "Automatically Sync with Folder" is TURNED OFF. "Insert SD Card" and "Allow Writes to SD Card" should be TURNED ON.

Right Click onto your SD.RAW, and Unmount it from your computer.

Click onto "File, Open" inside Dolphin. Navigate to where you had put your RB3Enhanced folder you had copied from your SD card. Select the .dol inside of this folder.

If Dolphin throws up a pop-up upon boot about stopping the current emulation, you either did not unmount your SD card, or select your SD.RAW in the SD CARD settings.

At this point Dolphin should now be booting up RB3E, now you just need to go to "File, Change Disk". Please select your copy of RB3 for the Wii.

Upon boot, the game will ask to "Save add-on content on the SD Card." You may hit either option and continue, ignore any popups about the SD card.

You should now be in the main menu, and your songs should be loaded in.

(If you would like to streamline the launching process, please make paths inside your Dolphin config tab to include where your RB3E.dol is, and where your RB3 ISO file is. Right click on your RB3ISO and select "Set as Default ISO". RB3E should now be visable within your games listed. You will now only need to click on this to start up RB3E.)

(please note, if you are not using (emulate disk speed), RB3E may halt when trying to boot. just retry it until it works.)
<br>
<br>

***WII***

(this requires a soft-modded wii with the homebrew channel. if you don't got that, look up a tutorial silly)

Install [RB3E](https://github.com/RBEnhanced/RB3Enhanced), and download [LavaManager](https://github.com/InvoxiPlayGames/LavaManager). 
Select your RB3 folder on your SD Card within LavaManager (it should automatically find it, try hitting LOAD SD CARD).
Drag over the "RB3" folder downloaded within each assigned export or DLC folder onto the root of your SD Card.
To double check and make sure you did it correctly, you should now see a (songs) and (lava) folder inside your RB3 folder.
Reload your song list on LavaManager, you *should* see the songs you downloaded load in.
Just hit finalize then exit Lava.

Upon boot, the game will ask to "Save add-on content on the SD Card." You may hit either option and continue, ignore any popups about the SD card.

You should now be in the main menu, and your songs should be loaded in.

# CURRENT ISSUES

Upgrades may not be available for every song, as I may of skimmed over it. Submit an issue if I forgot one, I will be happy to add it!

Currently drum mixes are just broken, this is due to RB3 Wii bein silly. Max of 2 drum tracks. (some official wii dlc was broken because of this too!)
A patched RB3DX for Dolphin and Wii that'll allow every drum mix is planned, but is just not uploaded yet. Be patient!
This shouldn't have any issue with how the songs sound, just if playing drums and you happen to miss certain stems may not mute.

If playing online with people with outdated upgrades for the same song, crashes may happen. Sorry :(

# DOLPHIN NOTES

You may increase your games framerate using the VBI Frequency Override found in your Config Tab on Dolphin. This has been [tested](https://youtu.be/oiP4LCsCtGg) with someone playing on real hardware and did not seem to cause any issues. Feel free to test it out, no promises tho.

While you are here, please hit Enable Emulated Memory Size Override, and drag (MEM2) to 128MB. This will greatly increase stability, and allow you to run the newest builds of Rock Band 3 Deluxe without crashing.

Please note if you are using the WIISDSYNC folder instead for your SD Card, you will have a very bad time.
I would highly suggest not to do this, and to follow the guide I had pasted above.

# ACKNOWLEDGEMENT

- https://github.com/RBEnhanced/RB3Enhanced
- https://github.com/InvoxiPlayGames/LavaManager
- https://github.com/rjkiv/rb3_plus
- https://github.com/FujiSkunk/rbhp
- https://github.com/rhythm-game-songs/rb4_plus

Without the contributions of the people behind these projects, none of this would be possible.
Sincerest thank yous!
