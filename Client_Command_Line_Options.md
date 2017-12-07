This document was created by man2html and the online WikiConverter <http://labs.seapine.com/htmltowiki.cgi>

It refers to Red Eclipse as installed by the system-install target.

## NAME

redeclipse - script to launch the Red Eclipse FPS game client

## SYNOPSIS

\[ **-h**homedir \] \[ **-p**packagedir \] \[ **-o**sauerdir \] \[ **-g**logfile \]

\[ **-df**{0|1} \] \[ **-dw**width \] \[ **-dh**height \] \[ **-du**{0..3} \] \[ **-dv**{0|1} \] \[ **-da**samples \] \[ **-dc**depth \] \[ **-dd**depth \] \[ **-ds**bits \]

\[ **-x**'command(s)' \] \[ **-k**{0|1} \] \[ **-v**{0..4} \] \[ **--help** \]

\[ **-ss**{0..3} \] \[ **-sm**servermaster \] \[ **-sa**servermasterport \]

## DESCRIPTION

Red Eclipse is a single-player and multi-player first-person ego-shooter, built as a total conversion of Cube Engine 2, which lends itself toward a balanced gameplay, with a general theme of agility in a variety of environments.

**redeclipse** is a script which executes the **redeclipse** binary from the */usr/lib/games/redeclipse* directory.

The recommended way to change the settings of the client are to edit the *config.cfg* and *init.cfg* files in the home directory.

The redeclipse client starts a local loopback server upon launch which it uses to connect to for singleplayer, hence many of the server options are accepted by the redeclipse binary as well (see **\[/cgi-bin/man/man2html?6 redeclipse-server redeclipse-server\]**(6)). To edit the specific settings related to the loopback server, use the *localexec.cfg* and *localinit.cfg* files in the home directory.

## CAVEATS

Many of these options will, if used, be permanently saved in the init.cfg file.

## OPTIONS

### Filesystem options

**-h***homedir*  
Sets your home directory to *homedir*. Red Eclipse will look for files in this directory in addition the normal installation directory. All user files will be written to the home directory. Defaults to *$HOME/.redeclipse/*.

**-p***packagedir*  
Includes the data files found in *packagedir*. Can be used for adding additional mods. Packages will be loaded in the order specified. By default redeclipse only includes data files in its working directory */usr/share/games/redeclipse/data/*, and in the *temp* subdirectory of the home directory.

**-o***sauerdir*  
Sets the path to your Sauerbraten directory. If Red Eclipse can find your Sauerbraten directory, you can load and play Sauerbraten maps from withing Red Eclipse.

**-g***logfile*  
Output log to *logfile*. Path is set relative to *homedir* unless a leading **'/**' is used

### Video options

**-df**{0|1}  
Turns fullscreen mode on or off. 0 to disable, 1 to enable. Defaults to 1.

  
This configuration is stored in init.cfg

**-dw***width*  
Sets screen width to *width*. If height not specified, also sets height to 3/4 of width. min is 320.

  
This configuration is stored in init.cfg

**-dh***height*  
Sets screen height to *height*. If width not specified, also sets width to 4/3 of height. min is 320.

  
This configuration is stored in init.cfg

**-du**{0..3}  
Set shader quality. 0 for none, 1 for shaders with fastest quality, max is 3. Defaults to 1 where hardware supports it.

  
This configuration is stored in init.cfg

**-dv**{0|1}  
Turns vertical sync on or off. 0 to disable, 1 to enable. Defaults to 0.

  
This configuration is stored in init.cfg

**-da***samples*  
Sets full-scene anti-aliasing (FSAA) to *samples* samples.

  
This configuration is stored in init.cfg

**-dc***depth*  
Sets colour depth (bits per pixel) to *depth*.

  
This configuration is stored in init.cfg

**-ds***bits*  
Sets stencil buffer bits to *bits*.

  
This configuration is stored in init.cfg

**-dd***depth*  
Sets z-buffer depth to *depth*.

  
This configuration is stored in init.cfg

### General options

**-xcommand1*;*command2*;*...**  
Executes a list of commands once Red Eclipse has started up.

**-k**{0|1}  
Enables or disables kid mode, which reduces blood and death effects somewhat. 1 enables reduced gore, defaults to 0.

  
This configuration is stored in init.cfg

**-v**{0..4}  
Sets verbosity. This affects how much information is printed to the console. 0 is the least verbose, 4 is the most verbose, defaults to 0.

  
This configuration is stored in init.cfg

**--help**  
Display this manpage

### Server options

**-ss***{0..3}*  
Sets the server type of the local server. 0 for local only, 1 for private, 2 for public, 3 for dedicated. Defaults to 1. If set as dedicated (3) redeclipse will act similarly to redeclipse-server and not start the GUI.

**-sm***servermaster*  
Connects to *servermaster* to get the list of available servers, defaults to play.redeclipse.net.

**-sa***servermasterport*  
Contacts the master server using port *servermasterport*, defaults to 28800.

## EXAMPLES

**redeclipse -p$HOME/mod/data**

  
Load data from an additional directory.

**redeclipse -h$HOME/redeclipse\_configs/**

  
Reads and writes the configuration files to the specified directory instead of *$HOME/.redeclipse/*.

**redeclipse -x'mode 7; trialweapon 0; map hinder**'

  
Sets game mode to time trial, trialmode weapon to empty hands, and starts a game on the map "hinder".

## AUTHORS

Red Eclipse's [main developers](Contributors#Team_Lead "wikilink") are Quinton "quin" Reeves and Lee "eihrul" Salzman

This manual page was written by Martin Erik Werner &lt;<martinerikwerner@gmail.com>&gt;

## HISTORY

Red Eclipse was forked as a continuation of the game Bloodfrontier, which in turn was based on the Cube2 engine and the Sauerbraten game. Red Eclipse and Sauerbraten are now developed in parallel.
