# UnityToSteamPublic
[Windows] Streamlining the upload from Unity to Steam. Milked-down version to protect NDA.

## This is the "Vague-Paths" version to protect Steam NDA
For the "way more intuitive version", go here, if you have access by being a Steam partner:
https://steamcommunity.com/groups/steamworks/discussions/0/1291817208490243818/

## Origins
Originally used for our Steam game, [Throne of Lies: The Online Game of Deceit](https//www.ThroneOfLies.com) 
We wanted to streamline the build process. The more automated, the better! 

## Instructions

1. Edit the contents to ensure your path matches via the constants at top.

2. REM (comment) out anything you don't want. Edit to your liking.

3. Save as .bat and give it admin privs (or remember to "run as admin"), dropped in root Unity PROJECT dir.

4. Launch it after you build.

```
@ECHO OFF
REM ##############################################################################################
REM # by Imperium42 Game Studio @ https://www.imperium42.com                                     
REM # 1 - Delete the old \windows_content\ contents												 
REM # 2 - Copy steam ./build/ contents to /<your_steam_content>/
REM # 3 - Launch Steamworks build page on default browser							 
REM # 4 - Launch PlayFab title data page on default browser (REM'd out for public, but as idea)
REM # 3 - Launch Steam upload batch file 														 
REM ##############################################################################################
```

## License: MIT. 
Do whatever you want with it. Customize it. Make it better.
No need to keep the "by", either.

I am in no way related to Steam other than being a Steamworks partner. This is my own code for me and is, in no way, official code.
