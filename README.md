# Escape Velocity Nova on Steam Deck (And other Linux)

1. Install Lutris
 - You may have to install a Wine runner, you can choose the latest version
 
2. Download the files:
 - Main game (right click and "save as", this a http link): http://download.escape-velocity.games/EV%20Nova.zip
 - 1280x800 prepatched exe: https://drive.google.com/open?id=1SrlJcznwJoCZHshnSGlmodWIuwHr-KoT
 - Widescreen Patch (see note at the end of doc): https://drive.google.com/file/d/1SrlJcznwJoCZHshnSGlmodWIuwHr-KoT
 
3. Setup a Prefix for Nova:
 
* Open Lutris, Click + (top left) > Locally installed game >
- Name: EV Nova
- Runner: Wine
 
* Game Options > 
- Executable: Browse to "EV Nova.exe"
- Working directory: **Important**, this should be the same folder as "EV Nova.exe", otherwise it will say "Plug-Ins folder not found"
- Wine prefix: Any folder where to store ~700mb of wine prefix files. You will never have to go into this folder. If you don't know what to put, you can put `/home/deck/evnovaprefix`
  
* Click Save
 
4. The game should now show up on your Lutris list of games
 
5. Click the game and click Play. After it creates the wine prefix, you may have to click Play again to start the game
 
* If you want to apply the Widescreen patch yourself, values are 1280, 800, 0, 0, 1280 (Note: It will be difficult to apply it thru Linux because of the way the exe works, I suggest doing it in windows. If you want to do it in Linux, select the prefix then click the second button and choose "Open Wine console" and do it from there)

* Controller configs are currently WIP
