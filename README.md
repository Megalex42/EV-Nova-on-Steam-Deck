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
- Executable: /run/media/mmcblk0p1/Lutris/evnova/drive_c/EV Nova/EV Nova.exe
- Working directory: /run/media/mmcblk0p1/Lutris/evnova/drive_c/EV Nova/
- Wine prefix: /run/media/mmcblk0p1/Lutris/evnova/
 
* Runner Options > 
- Wine version: Choose any version that works (I used lutris-fshack-7.2-x86_64. These can be installed with ProtonUp-Qt app)
- Enable dgvoodoo2 (may not be necessary)
 
* Click Save
 
4. The game should now show up on your Lutris list of games
 
5. Click the game and click Play. After it creates the wine prefix, it'll give an error that the executable is not found. Click ok.
 
6. Move all EV Nova files to the Prefix, so your game should be in 
 
- /run/media/mmcblk0p1/Lutris/evnova/drive_c/EV Nova/
 
- Also make sure EVNovaPatcher.exe is in the same folder as EV Nova.exe
 
6. Go back to Lutris, Click Play again, see if the game works. Then exit the game.
 
7. While selecting the game Click the second button from the left, at the bottom, and choose "Run exe inside prefix", and run the Widescreen patch. Values are 1280, 800, 0, 0, 1280

* Controller configs are currently WIP
