Some servers offer the option to play on unofficial, custom maps, or to create new maps from scratch in a multiplayer editing session. In this case, new maps are fetched from the server and stored locally.

## Map files

Usually when a player joins an editing game or a match on a custom map, all needed files for the map will be downloaded automatically:

-   *name*.mpz - binary map content (geometry, materials, entities, light maps etc.)
-   *name*.cfg - configuration data (lists of textures, sounds, models, scripts etc.)
-   *name*.png - preview (a small screenshot)
-   *name*.txt - [license/readme](Copyright_and_Licensing_for_Contributions "wikilink") (if available)
-   *name*.wpt - [waypoints](waypoints "wikilink") (a navigation mesh for bots, if available)

**Note**: Custom textures, models or sounds are not uploaded to or retrieved from a server. Maps are still playable if such custom content is missing, though.

## Retrieving custom maps

In some cases, a player can get stuck in the loading screen, or map synchronization issues might arise. In this case, the map can be retrieved again using a [console](console "wikilink") command:

`   /getmap`

If this command fails to get the map data, ask a fellow player to (re-) upload the local map data to the server:

`   /sendmap`

If loading the map still fails, leaving the server and connecting again might fix the issue:

`   /reconnect`

If this not does help either, you might already have a map of the same name in your [user maps](custom_maps#user_map_storage "wikilink"). Try moving or deleting the corresponding files and then reconnect to the server.

**Note**: Players with different map versions (of the same map name) can cause synchronization issues not only for their own client. In some cases, it may be necessary that everyone connected to the server is using the same map version.

## Temporary map storage

Any map ever retrieved from a server will be stored automatically in a subdirectory of the [user content](Game_Settings#User_Content "wikilink") directory:

Windows

`   C:\Users\`<username>`\My Documents\My Games\Red Eclipse\temp\maps`

Linux

`   ~/.redeclipse/temp/maps/`

OSX

`   /Home/Library/Application Support/redeclipse/temp/maps`

## User map storage

To make a map easily accessible from the maps menu (F4), the corresponding files can be moved or copied to another subdirectory **maps** of the [user content](Game_Settings#User_Content "wikilink"). For instance on linux:

`  cp ~/.redeclipse/temp/maps/exampleMapName.* ~/.redeclipse/maps`

**Note**: There is no need to put any custom maps in the install directory of Red Eclipse, just keep them in the maps folder of your [user content](Game_Settings#User_Content "wikilink").

## Saving maps

Of course, a copy of the current map can be saved any time, and not only during an editing game:

`   /savemap `<newmapname>

This will create (and **overwrite**) the corresponding files in the maps folder of the [user content](Game_Settings#User_Content "wikilink"):

-   *newmapname*.mpz
-   *newmapname*.cfg
-   *newmapname*.png

