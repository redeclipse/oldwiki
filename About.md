***Red Eclipse*** is a [multi-platform](Cross-platform "wikilink"), [free](Free_software "wikilink"), and [open source](open_source "wikilink") [first-person](first-person_shooter "wikilink") arena shooter that runs on a somewhat modified [Cube Engine 2](Cube_2:_Sauerbraten "wikilink"). The game is centered on [multiplayer](multiplayer "wikilink") based action, but can also be played offline against [bots](Computer_game_bot "wikilink").[1]

## Gameplay

![Red Eclipse screenshot (Elara 1.4.1)](Red Eclipse screenshot (Elara 1.4.1).png "fig:Red Eclipse screenshot (Elara 1.4.1)") *Red Eclipse* is a multiplayer first-person arena shooter with a style of play comparable *[Quake III Arena](Quake_III_Arena "wikilink")* or *[Unreal Tournament](Unreal_Tournament "wikilink")*,[2] [3] though the lead developer claims it was intended as a subversion of common mechanics in the arena FPS subgenre. [4]

The game consists of a variety of [modes](Game_mode#Game_modes "wikilink"), which can be extended with any of fourteen "mutators". For example, the "Deathmatch" mode can be used in conjunction with the "Instagib" and/or "Survivor" mutators, changing how the game is played. This allows players to experience more flexibility and variety when playing the same mode. There are also seven mode-exclusive mutators, which can only be played in certain modes.

Aside from the more traditional modes of its genre - among them "[Deathmatch](Deathmatch "wikilink")", "[Capture the Flag](Capture-the-flag "wikilink")", and "Defend and Control" (akin to [King of the Hill](King_of_the_Hill_(game) "wikilink")), *Red Eclipse* offers two more modes of play. "Bomber-Ball" pits two teams against one another with the objective of throwing the bomb into the enemy team's "goal" before it explodes, and "Race", in which players race through a map to compete for the best times or number of laps.

Bots are also available for all modes and mutators when teams are short of human players, as well as for offline practice matches.

*Red Eclipse's* weapon arsenal consists of a pistol, sword, shotgun, submachine gun, flamethrower, plasma gun, zapper, rifle, grenade, mine and rocket launcher, [5] each with primary and alternate methods of attack. Weapons also have variables that can be changed on a server level that alter to change their behavior, such as particle size, accuracy, the reload and fire rates, and damage. Players with the correct level of access can modify these on-the-fly during a game to change the gameplay experience.

### Movement and physics

The game's "Impulse" and [parkour](parkour "wikilink") systems allow the player a variety of ways to move about a level via wall-kicking, wall-running, dashing on the ground and mid-air, and double-jumping. [6] Similarly to the weapon variables, there is also a list of environmental variables, allowing players to easily create their own unofficial modes. Variables pertaining to physics, such as jump height or distance, movement speed, and gravity.

### Game modes and mutators

*Red Eclipse* has six different game modes excluding the in-game editor and demo: [Deathmatch](Deathmatch "wikilink"), [Capture-the-flag](Capture-the-flag "wikilink"), [Defend-and-control](Defend-and-control "wikilink"), [Bomber-ball](Bomber-ball "wikilink") and [Race](Race "wikilink").

By default, the game is on team play (Alpha team vs. Omega team) unless the player selects FFA or Multi mutators

In addition to the game modes, there are fourteen mutators which extend the game modes:

1.  FFA (Free For All) – All vs. All
2.  Multi – 4 teams battle
3.  Coop – Humans are put on one team to fight against bots.
4.  Instagib – One shot kills (Via health set to 1) and snipers only. The rifle can be changed to sword or grenades and mines using Medieval or Kaboom mutators respectively.
5.  Onslaught – Adds neutral waves of bots and turrets to fight.
6.  Vampire – Hurting other people increases the attacker's health.
7.  Medieval – Swords only.
8.  Kaboom – Grenades and mines only.
9.  Classic – Weapons must be collected from spawns in the arena, similar to previous versions of the game
10. Hard – Radar and health regeneration disabled.
11. Duel – Two people at a time; other players on a server observe and wait. (With Multi mutator there are 4 players at a time)
12. Survivor – Everyone spawns at once then the last man standing wins.
13. Freestyle – Players can use unlimited impulse moves.
14. Resize – Everyone changes size depending on their health.
15. Basic – No item pickups are spawned in the arena.

Furthermore, *Red Eclipse*'s individual modes could have multiple "mutators" enabled or disabled to extend the mode, such as having Capture the Flag with the Instagib, Teamplay, and jetpack mutators, which enables one-shot-one-kill styled gameplay, and players to fly around.

It also has some support for [Sauerbraten](Cube_2:_Sauerbraten "wikilink") maps, allowing players to play various Sauerbraten maps. However, due to Sauerbraten not having the same movement and game mechanics and weapons, the maps often don't play too well in Red Eclipse.

## Development

*Red Eclipse* is built upon the [Cube Engine 2](Cube_2:_Sauerbraten "wikilink"). The first version 1.0 was released on the 15th of March, 2011.[7] The game code is under the [permissive Free](Permissive_free_software_license "wikilink") [zlib License](zlib_License "wikilink"), and the game data assets are mainly under the [Copyleft](Copyleft "wikilink") License [CC-BY-SA-3.0](Creative_Commons_licenses "wikilink"). [8]

## Technical details

<img src="Sauer editing-1--.png" title="fig:An example of a primitive cube subdivision provided by Cube 2 engine" alt="An example of a primitive cube subdivision provided by Cube 2 engine" width="140" /> *Red Eclipse* utilizes the Cube 2 engine, which uses a 6-directional heightfield (or [octree](octree "wikilink")) world model. An octree in Red Eclipse is a cube that can be split into eight smaller cubes that can then be done the same to. This allows for complex level geometry and easier editing which can be accomplished through the game's built in editor.

### Rendering engine

The original *[Cube](Cube_(video_game) "wikilink")* engine's rendering engine assumed that overdraw (where polygons that do not appear in the final scene are occluded via the [z-buffer](z-buffering "wikilink")) was more processor-intensive than sending new streams of triangles to the graphics processing every frame, which limited its performance on more modern hardware where [memory bandwidth](memory_bandwidth "wikilink") is a greater limiting factor. Instead, *Red Eclipse* uses the [rendering engine](Rendering_(computer_graphics) "wikilink") in Cube 2, which is designed around modern graphics processing units, which perform best with huge batches of geometry already stored in video memory. Lighting is precomputed into [lightmaps](lightmap "wikilink")—image files that correspond to geometry as textures—for efficient batching, with an additional stored directional component, that allows for efficient [shader](shader_(computer_science) "wikilink")-based lighting effects.

## Map editor

<img src="Screenshot of Fortitude,a Red Eclipse map,being edited.png" title="fig:Red Eclipse uses the Cube 2 engine&#39;s map editor, which allows for maps to be easily made in-game" alt="Red Eclipse uses the Cube 2 engine&#39;s map editor, which allows for maps to be easily made in-game" width="320" /> *Red Eclipse* retains the Cube 2 engine's built-in map editor, in which the player can to fly around the game world manipulating and deforming volumes referred to as cubes. This, as well as weapon and other entity placement is achieved in real-time, and can be done cooperatively online with other players as well. [AI](Artificial_Intelligence "wikilink") "waypoints" can also be generated dynamically as the map is played. Lighting is accomplished through precomputed [lightmaps](Lighting "wikilink"). Each cube-shaped node in the [octree](octree "wikilink") represents a renderable volume, simply referred to as a *cube*. Each edge of this cube can be lengthened or shortened to deform the cube into a variety of other shapes. Corners of cubes can also be "pushed" or "pulled" to create crude curves.

The what you see is what you get (WYSIWYG) realtime editing ability enables level designers to add a plethora of detail to maps, while reducing the time spent on actual creation. This is in contrast to the traditional modern [polygon soup](polygon_soup "wikilink") 3D engines which take a model generated as an essentially random batch of triangles from an external modelling program, and attempt to [spatially subdivide](spatial_subdivision "wikilink") the model's triangles after the fact by splitting them to fit into tree structures, such as a [BSP tree](binary_space_partitioning "wikilink") or even an [octree](octree "wikilink"), that require costly pre-processing to render.

## Reception and impact

![[Microsoft Research](Microsoft_Research "wikilink") [IllumiRoom](IllumiRoom "wikilink") proof-of-concept, on the screen Red Eclipse](IllumiRoom.png "fig:Microsoft Research IllumiRoom proof-of-concept, on the screen Red Eclipse") The Hungarian [Gamestar](Gamestar "wikilink") website reviewed the Red Eclipse predecessor, Blood Frontier, in December 2009.[9] *Red Eclipse* was favourably reviewed by German game magazine [Chip.de](Chip.de "wikilink") on October 2013.[10]

Red Eclipse was also used by researchers of the [University of Illinois at Urbana-Champaign](University_of_Illinois_at_Urbana-Champaign "wikilink") and [Microsoft Research](Microsoft_Research "wikilink") for showcasing [IllumiRoom](IllumiRoom "wikilink"), a [augmented](augmented_reality "wikilink") [television](television "wikilink") screen with projectors project, on the [CHI 2013](Conference_on_Human_Factors_in_Computing_Systems "wikilink").[11][12][13]

## See also

-   *[Cube 2: Sauerbraten](Cube_2:_Sauerbraten "wikilink")*

## References

<references>
</references>
## External links

-   -   [Official site of the Cube engines](http://strlen.com/cube/)
-   [The Red Eclipse gaming monitor](http://redflare.ofthings.net/)
-   [Red Eclipse: Weaponry Development](http://www.instructables.com/id/Red-Eclipse-Weaponry-Development/)

[1] 

[2] 

[3] 

[4] 

[5] 

[6] 

[7] [Red Eclipse, An Open Source FPS](https://www.rockpapershotgun.com/2011/03/20/red-eclipse-an-open-source-fps/) on [Rock, Paper, Shotgun](Rock,_Paper,_Shotgun "wikilink") by [Jim Rossignol](Jim_Rossignol "wikilink") (March 20, 2011)

[8] 

[9] [Blood Frontier: ingyenesen letölthető!](http://www.gamestar.hu/hir/blood-frontier-ingyenesen-letoltheto-43295.html) on [Gamestar](Gamestar "wikilink") (in Hungarian, December 2009)

[10] [Red Eclipse for Windows](http://www.chip.de/downloads/Red-Eclipse-fuer-Windows-Galactic-Edition_48022095.html) *"Die CHIP Redaktion sagt: "Red Eclipse" ist ein kostenloser Open-Source-Ego-Shooter, der durch viele Maps und eine rasante Spielmechanik punktet."* on [Chip.de](Chip.de "wikilink") (in German, October 2013)

[11] [IllumiRoom\_CHI2013](http://research.microsoft.com/en-us/projects/illumiroom/IllumiRoom_CHI2013_BJones.pdf) by Microsoft Research *"The majority of the illusions were paired with an open-source first-person shooter (Red Eclipse). This created a rich, interactive experience, enabled by access to source code."*

[12] 

[13] 
