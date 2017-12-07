If you have a nice server example, feel free to share it here. For info on running the server, see [Server Command Line Options](Server_Command_Line_Options "wikilink") or read the manual.

## [Edit](Editing "wikilink") Mode Server

**servexec.cfg:**

    // This file controls server side variables which influence gameplay (which must be prefixed with 'sv_')
    // It is executed whenever variables are reset (on start, and whatever 'resetvarsonend' tells it to)

    sv_serverclients 6
    sv_serverdesc "CoopEdit"
    sv_servermotd "F1 key toggles Edit View, F2 key for Textures menu, F3 key for Edit menu"
    sv_timelimit 0
    sv_resetbansonend 0

    sv_defaultmode 0
    sv_defaultmap "myfirstmap"

    sv_varslock 1
    sv_modelock 0
    sv_mapslock 0

    sv_rotatemuts 0
    sv_rotatemode 0

    sv_resetvarsonend 2

    sv_maprotate 2

    sv_allowmaps "" // allowed maps
    sv_campaignmaps "" // campaign maps
    sv_mainmaps "" // deathmatch maps
    sv_capturemaps "" // capture-the-flag maps
    sv_defendmaps "" // defend-the-flag maps
    sv_bombermaps "" // bomber-ball maps
    sv_holdmaps "" // hold bomber-ball maps
    sv_racemaps "" // race maps

## 1 vs 1, 2 vs 2 [Survivor](Mutator_Tips#survivor "wikilink") Team Arena Server

-   This server has quick respawn, quick map rotation, and voting disabled

**servexec.cfg:**

    // This file controls server side variables which influence gameplay (which must be prefixed with 'sv_')
    // It is executed whenever variables are reset (on start, and whatever 'resetvarsonend' tells it to)

    sv_serverclients 4
    sv_resetbansonend 0
    sv_serverdesc " 2 vs 2 Duel Arena"
    sv_servermotd "Press F6 or Comma (,) to Change Weapons"

    sv_timelimit 6

    sv_resetvarsonend 1

    sv_intermlimit 6000 // time in milliseconds intermission lasts
    sv_votelimit 0 // time in milliseconds intermission voting lasts
    sv_duellimit 1000 // time in milliseconds before next round in duel/survivor

    sv_teambalance 2 // determines the method of team balancing; 0 = off, 1 = by number, 2 = by rank, 3 = humans vs. ai
    sv_botbalance 1
    sv_botlimit 2
    sv_skillmin 95
    sv_skillmax 95


    sv_defaultmode 3
    sv_defaultmuts 194
    //sv_defaultmap ""

    sv_varslock 1
    sv_modelock 1
    sv_mapslock 1

    sv_rotatemuts 0
    sv_rotatemode 0

    sv_resetvarsonend 0


    sv_instadelay 500 // time in milliseconds before players can respawn in instagib mutated modes

    sv_allowmaps "bath echo dutility darkness deathtrap lab mist panic" // allowed maps
    sv_mainmaps "bath echo dutility darkness deathtrap lab mist panic" // deathmatch maps
    sv_maprotate 1

## Race server

-   This server has no time limit and therefore votestyle 1.
-   Custom race maps are added to the rotation by parsing a backup directory.

**servexec.cfg:**

    // This file controls server side variables which influence gameplay (which must be prefixed with 'sv_')
    // It is executed whenever variables are reset (on start, and whatever 'resetvarsonend' tells it to)

     adminpass thereIsNoSpoon   // password to claim administrator rights via /setpriv
     sv_serverclients 10        // maximum number of allowed clients
     sv_serverdesc "Time race" // server description shown in the F4 menu
     sv_servermotd "Here goes the message shown upon login. Custom content should be declared here. ^n Line breaks can help to structure a longer motd."

     sv_defaultmap        "neodrive"    // default map, "" = random
     sv_defaultmode       $modeidxrace // default game mode, convenient to set using a sum of $modeidx* vars 
     sv_modelockfilter    $modebitrace // determines the modes available in the vote menu
     sv_rotatemodefilter  $modebitrace // determines the mode rotation when the server selects the next map
     sv_defaultmuts       (+ $mutsbitffa $mutsbitclassic ) // default mutators, convenient to set using a sum of $mutsbit* vars 
     sv_rotatemutsfilter  (+ $mutsbitffa $mutsbitclassic ) // determines the mutator rotation when the server selects the next map
     
     sv_timelimit 0        // disable the time limit, therefore voting must be possible mid-match 
     sv_votestyle 1        // the vote passes when a majority of the players agrees on the next match
     sv_votethreshold 0.51 // the majority is defined as 51%, i.e. more than half of the players

     sv_teamneutralcolour 0xffffff // most race games are FFA - a custom color (white) enhances the visibility of players.

    // Assume that the directory "racemaps" in your user data holds a backup of your favorite extra maps (or just of the cfg files).
    // Here we set the race maps available in the vote menu by parsing that directory.
     maplist = $sv_racemaps
     loopfiles i racemaps cfg [ 
         maplist = (concat $maplist $i)
     ]
     sv_racemaps $maplist

## Classic variables

It is also possible to use customized game variables. By adding the following lines, the game rules for weapons and movement are very similar to Red Eclipse 1.4.

    // server variables for classic weapons and movement (Elara edition r6550)
    sv_flamerammoadd 50
    sv_flamerammomax 50
    sv_flamerammosub2 5
    sv_flamerdamage1 7
    sv_flamerdamage2 7
    sv_flamerdamagehead2 1.0
    sv_flamerdamagelegs2 1.25
    sv_flamerdelayattack1 150
    sv_flamerdelayattack2 750
    sv_flamerdelayreload 1250
    sv_flamerelasticity1 0.5
    sv_flamerelasticity2 0.35
    sv_flamerexplode1 8.0
    sv_flamerflakdamage1 7
    sv_flamerflakdamage2 7
    sv_flamerflakdamagelegs2 1.25
    sv_flamerflakelasticity1 0.5
    sv_flamerflakelasticity2 0.35
    sv_flamerflakexplode1 8.0
    sv_flamerflakhitpush2 75.0
    sv_flamerflakpartsize1 10.0
    sv_flamerhitpush2 75.0
    sv_flamerkickpush2 25.0
    sv_flamerpartsize1 10.0
    sv_flamerspeed2 1000
    sv_flamertaperin1 0.25
    sv_flamertime1 265
    sv_flamertime2 110
    sv_grenadedamageteam1 0.0
    sv_grenadedamageteam2 0.0
    sv_grenadeexplcol1 0x981808
    sv_grenadeexplcol2 0x981808
    sv_grenadeflakdamageteam1 0.0
    sv_grenadeflakdamageteam2 0.0
    sv_grenadeflakexplcol1 0x981808
    sv_grenadeflakexplcol2 0x981808
    sv_grenadeflakhitpush1 250.0
    sv_grenadeflakhitpush2 250.0
    sv_grenadefragtimedelay1 3
    sv_grenadefragtimedelay2 3
    sv_grenadehitpush1 250.0
    sv_grenadehitpush2 250.0
    sv_minedamage1 150
    sv_minedamage2 150
    sv_minedamageteam1 0.0
    sv_minedamageteam2 0.0
    sv_mineexplcol1 0x00F068
    sv_mineexplcol2 0x00F068
    sv_mineflakdamage1 150
    sv_mineflakdamage2 150
    sv_mineflakdamageteam1 0.0
    sv_mineflakdamageteam2 0.0
    sv_mineflakexplcol1 0x00F068
    sv_mineflakexplcol2 0x00F068
    sv_minefragtimedelay1 5
    sv_minefragtimedelay2 100
    sv_minerelativity1 0.65
    sv_minerelativity2 0.65
    sv_pistoldelayattack1 125
    sv_plasmaaiskew1 3
    sv_plasmaaiskew2 3
    sv_plasmaammoadd 20
    sv_plasmaammomax 20
    sv_plasmaammosub2 20
    sv_plasmacooked2 33
    sv_plasmadamage1 15
    sv_plasmadamagelegs1 0.2
    sv_plasmadamagelegs2 0.2
    sv_plasmadamageteam2 0.0
    sv_plasmadelayattack1 300
    sv_plasmaexplode1 8.0
    sv_plasmaflakdamage1 15
    sv_plasmaflakdamagelegs1 0.2
    sv_plasmaflakdamagelegs2 0.2
    sv_plasmaflakdamageteam2 0.0
    sv_plasmaflakexplode1 8.0
    sv_plasmaflakhitpush2 -50.0
    sv_plasmaflakpartsize2 24.0
    sv_plasmahitpush2 -50.0
    sv_plasmapartsize2 24.0
    sv_plasmataperin1 0.005
    sv_plasmatime1 355
    sv_rifleaiskew1 2
    sv_rifleaiskew2 2
    sv_riflecooktime2 0
    sv_rifledamage1 45
    sv_rifledamage2 150
    sv_rifledamagelegs1 0.2
    sv_rifledamagelegs2 0.2
    sv_rifledamagetorso1 0.4
    sv_rifledamagetorso2 0.4
    sv_rifledelayattack1 750
    sv_rifledelayattack2 1500
    sv_rifleexplode1 8.0
    sv_rifleflakdamagelegs1 0.2
    sv_rifleflakdamagelegs2 0.2
    sv_rifleflakdamageteam1 0.0
    sv_rifleflakdamageteam2 0.0
    sv_rifleflakdamagetorso1 0.4
    sv_rifleflakdamagetorso2 0.4
    sv_rifleflakexplcol1 0x00F068
    sv_rifleflakexplcol2 0x00F068
    sv_rifleflakexplode2 8.0
    sv_rifleflakhitpush1 0.0
    sv_rifleflakhitpush2 0.0
    sv_rifleflakpartcol1 0x00F068
    sv_rifleflakpartcol2 0x00F068
    sv_rifleflakpartsize1 1.0
    sv_rifleflakresidual1 4
    sv_rifleflakresidual2 4
    sv_rifleflakwavepush1 2.5
    sv_rifleflakwavepush2 1.5
    sv_riflehitpush1 75.0
    sv_riflehitpush2 150.0
    sv_riflepartsize1 2.0
    sv_riflespread1 1.5
    sv_rocketdamageteam1 0.0
    sv_rocketdamageteam2 0.0
    sv_rocketexplcol1 0x981808
    sv_rocketexplcol2 0x981808
    sv_rocketflakdamageteam1 0.0
    sv_rocketflakdamageteam2 0.0
    sv_rocketflakexplcol1 0x981808
    sv_rocketflakexplcol2 0x981808
    sv_rocketflakhitpush1 500.0
    sv_rocketflakhitpush2 500.0
    sv_rocketflakwavepush1 4.0
    sv_rocketflakwavepush2 4.0
    sv_rocketfragtimedelay1 3
    sv_rocketfragtimedelay2 3
    sv_rockethitpush1 500.0
    sv_rockethitpush2 500.0
    sv_rocketwavepush1 4.0
    sv_rocketwavepush2 4.0
    sv_shotgunaiskew1 5
    sv_shotgunaiskew2 5
    sv_shotgundamage1 8
    sv_shotgundamage2 4
    sv_shotgundelayattack1 750
    sv_shotgundelayattack2 1250
    sv_shotgundelayreload 750
    sv_shotgunflakdamage1 8
    sv_shotgunflakdamage2 8
    sv_shotgunflakdamageteam2 0.0
    sv_shotgunfragrays2 20
    sv_shotgunrays1 20
    sv_smgaiskew1 2
    sv_smgaiskew2 2
    sv_smgammoadd 50
    sv_smgammomax 50
    sv_smgammosub2 5
    sv_smgdamage1 18
    sv_smgdamage2 5
    sv_smgdelayattack2 500
    sv_smgflakdamage1 18
    sv_smgflakdamage2 5
    sv_smgflakdamageteam2 0.0
    sv_smgfragtimedelay2 3
    sv_smgtaperin1 0.005
    sv_sworddamage1 32
    sv_sworddamage2 64
    sv_sworddelayattack1 600
    sv_swordflakdamage1 32
    sv_swordflakdamage2 64
    sv_swordflakstunfall1 0.0
    sv_swordflakstunfall2 0.0
    sv_swordflakstunscale1 1.0
    sv_swordflakstunscale2 2.0
    sv_swordstunfall1 0.0
    sv_swordstunfall2 0.0
    sv_swordstunscale1 1.0
    sv_swordstunscale2 2.0
    sv_zapperdisabled 1
    sv_zoomtime 100
    //movement
    sv_impulsedash 1.2
    sv_impulsedashdelay 1000
    sv_impulsejumpdelay 250
    sv_impulseparkourclimb 1.3
    sv_impulseparkourkick 1.3
    sv_impulseparkourvault 1.4
    sv_movespeed 100
    sv_moverun 1.6
    sv_slidecoastscale 0.25
    sv_impulseregen 7.0
