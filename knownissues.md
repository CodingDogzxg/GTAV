# Known Bugs and Errors

> B = Bug - E = Error - F = Fix

**B:** When I create "Vehicles" Widgets, the game crashes.<br>
**F:** Before Opening The Save Game, just enter the game normally and dont load the save, create vehicle widgets then load the game.

**E:** Fatal Error: Unable to create default effect 'common:/shaders/im', cannot continue.<br>
**F:** If u didn't put the shaders to the game directory or you dont have the low quality shaders, then this error may appear.

#### Solution 1: 
Just Simply Put the shaders to the game directory and compile the low quality shaders by following tutorial.

#### Solution 2:
Just make your shaders quality "High" and dont lower that.<br>
To do this, Follow this steps:

1. Go To **\Documents\Rockstar Games\GTA V**
2. Open *settings.xml*
3. Change  `<ShaderQuality value="0" />` To `<ShaderQuality value="1" />`
4. Save the file and Done!

**E:** Couldn't connect to RAG.exe. Keep trying?<br>
**F:** Just Simply Open the RAG Manually, then start **launch.bat**.

**E:** Fatal Error: Fatal disc error (code -*)<br>
**F:** You are %100 missing some files or misdragged something, fix your game files.

# Known Issues
* Game crashes if you open "Keybinds" Menu in BankRelease or Debug Builds.
  * It's because the game tries to load a missing keyboard layout file.
    * This can be fixed by just editing some lines in the source code.
  
