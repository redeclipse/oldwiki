## Purpose

Red Eclipse allows to record the game action of a match in a compact file format (*.dmo*). These demo or replay files contain all relevant game settings and the user input of each player. Demo playback allows to experience and analyze the game action from any chosen perspective, including each player's point of view.

**Important**: Demo files are necessary evidence when reporting violations against the [Multiplayer Guidelines](Multiplayer_Guidelines "wikilink").

## Fetching demos

Per default, public game servers record a demo for every new match while keeping the files of the latest ten matches. These demo files can be listed any time using the [console](console "wikilink"):

    /listdemos

This will show a numbered list of demos including time stamps. The demo files can be downloaded using:

    /getdemo <number>

If no number is specified, this will fetch the latest demo available. The very same procedure can be used to save demo files when playing offline, too. Note that the match must end before its demo can be obtained.

## Demo playback

Demo playback is only possible when playing offline. A convenient way to pick a demo file is to open the *offline practice* game menu (F3) and to select the *demo* checkbox among the game modes at the top left.

You can also start demo playback via the [console](console "wikilink") and use the *Tab* key for auto-completion of the filename:

    /demo <filename>

During demo playback, the player is locked in spectator mode. The mouse scroll wheel can be used to watch the action from different points of view, and as usual, *F9* allows to toggle first or third person view. Note that spectator mode is also available any time during live games and can be entered using the *Home* key (default key bindings).

The playback speed of a demo can be altered using the variable *sv\_gamespeed* (because the variable *gamespeed* is among the gameplay variables stored in the file). For example, the following [key bind](Keybinding#Onrelease "wikilink") can be used to fast-forward by holding the F key:

`/specbind "F" [sv_gamespeed 10000; onrelease sv_gamespeed 100]`

## Renaming demos

All *dmo* files fetched from game servers can be found in the *demo* subdirectory in the [user content](Game_Settings#Location "wikilink"). Per default, these files are named according to a time-stamp format:

    YYYYMMDDhhmmss.dmo

These files can be renamed at will, but should be kept in the *demo* directory such that they can be listed in the F2 menu.
