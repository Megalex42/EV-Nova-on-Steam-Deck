# EV-Nova-on-Steam-Deck

1. Install Lutris
 - Install Flatseal, in flatseal, go to "All Applications" on the left, then scroll down to Filesystem and enable the bullet next to "All user files"
    in the section "Other Files", put in /run/media/mmcblk0p1, then close flatseal (may not be necessary)
 
2. Download the files:
 - main game: http://download.escape-velocity.games/EV%20Nova.zip
 - widescreen patch: https://drive.google.com/open?id=1SrlJcznwJoCZHshnSGlmodWIuwHr-KoT
 
3. Setup a Prefix for Nova:
 
- Click + > Locally installed game >
- Name: EV Nova
- Runner: Wine
 
* Game Options > 
- Executable: Browse to "EV Nova.exe"
- Working directory: Important, this should be the same folder as "EV Nova.exe"
- Wine prefix: Any folder where to store ~700mb of wine prefix files.
  
* Click Save
 
4. The game should now show up on your Lutris list of games
 
5. Click the game and click Play. After it creates the wine prefix, you may have to click Play again to start the game
 
- Make sure EVNovaPatcher.exe is in the same folder as EV Nova.exe
 
6. While selecting the game Click the second button from the left, at the bottom, and choose "Run exe inside prefix", and run the Widescreen patch. Values are 1280, 800, 0, 0, 1280

* Controller configs are currently WIP
