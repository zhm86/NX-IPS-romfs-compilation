## About this project

This is a romfs and IPS mod compilation from various authors, it's a community effort though the years so I don't take all the credit.

Most of these mods focus on resolution and graphical features like shadow resolution, draw distance, textures quality, etc. rather than framerate performance, I've personally tested them to run optimal at 30 FPS, some games will still work at 60 FPS with [FPSLocker](https://github.com/masagrator/FPSLocker)

## Requisites

* To use these mods you will need a Switch with atmosphere installed, you MUST use overcloking for the 90% of these mods, some mods are quite demanding so be prepared to use at least RAM@2400, GPU@1228, CPU@1500. More info about how setup overclocking https://rentry.co/mariko

* **Important**: all the mods were tested and tailored for Mariko Switch, while most mods can work on Erista they were not optimized for it.

## Usage

* Make sure read the file `description.txt` included in each game as it contains important information about the mod itself, files needed, and what the mod does. It also includes the respective author of the mod, please contact through an "Issue" if you haven't been mentioned in a certain mod.

* Each folder contains mods for that particular game, `release_X.X.X.rar` contains the files ready to copy to your atmosphere folder, no other step is needed.

* The mod will only work for the version indicated in `description.txt`

* Some games use a different folder tittle ID (TID) and/or build ID (BID) for their physical releases, Crysis Remastered for example has a different TID and BID for the physical and digital versions.

* **Advanced**: When apply a `*.pchtxt` file is included in the game folder, you can use it edit the mod to your liking, I tried to document the best I could each instruction. Atmosphere only will read mods in IPS format, pchtxt must be converted to IPS. Use [IPSwitch](https://github.com/3096/ipswitch) or [Ultrahand](https://github.com/ppkantorski/Ultrahand-Overlay) Mod Alchemist

* **Advanced**: When apply a `UE.ini` folder is provided, you can edit ini files to your liking and re-pack into an UnrealEngine patch.
More info about UE unpacking-packing can be found here https://gbatemp.net/threads/how-to-unpack-and-repack-unreal-engine-4-files.531784/

## About opening Issues

* Only open issues to report problems like crashes, graphical glitches, sound problems, etc. It's not a place to post request, they will be ignored.

* When opening a new issue make sure you are using the latest version of the game, old versions are unsuported.

* Make sure add all the relevant information about the issue include all possible details.

* Before open an issue test using pchtxt first instead IPS (it could be possible I missed something at the moment to create the IPS)

## Credits and thanks

- @hanai3bi, @B3711 for OC Switchcraft EOS
- @MasaGratoR for his valuable help, tips, and tools
- @ECLIPSE00074 for his amazing graphic mods
- @Hazerou, @theboy181, @KeatonTheBot, @Stevens, @Fl4sh_ modders 
- @b0rd2death for his handy mod manager tool
- All the people testing stuff over NSwitch 60 FPS Cheats & Mods
