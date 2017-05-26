# UnityToSteamPublic
[Windows] Streamlining the upload from Unity to Steam. Milked-down version to protect NDA.

1. Edit the contents to ensure your path matches via the constants at top.

2. REM (comment) out anything you don't want. Edit to your liking.

3. Save as .bat and give it admin privs (or remember to "run as admin"), dropped in root Unity dir.

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
