When creating a new map, it can be interesting to test a different scale, for instance to double the size of all geometry.

### Quick test

To get a first impression, the variable *playerscale* is convenient to use, for example:

`   /playerscale 0.5`

This shrinks the player models by a factor of two, so the map appears to be twice as large. Note that this method has some limitations. In particular, the step size of stairs or the water depth for swimming remains constant (so it appears to have increased as well).

### Step by step instructions

In order to change the actual scale of the map, it is recommended to follow these steps (in brackets: Default key binds or /commands):

1.  make a backup of your map and waypoints (/savemap bak; /savewaypoints bak)
2.  pick the largest grid size for convenience (G + mouse wheel)
3.  select all geometry (e.g. left click on bottom front left, then right click on top back right corner)
4.  select all entities (/entfind)
5.  copy and delete everything (C, then Backspace)
6.  if necessary, increase the map bounds (/mapenlarge)
7.  lower or increase the grid size (G + mouse wheel)
8.  paste the geometry and all entities (V)
9.  if you scaled down the map, you may want to adjust the bounds (/shrinkmap)
10. recalulate the lightmap (F7)
11. save the scaled map (/savemap test)
12. fine tuning: See the next section

### Limitations

The method described above has some limitations. Therefore, it may need some more work to properly scale a map. Currently, there is no way to scale the map's waypoints, so they need to be recreated. Furthermore, some entities may need further adjustments:

1.  check for lost entity links (triggers, teleports, routes etc)
2.  check for lost entites attributes(e.g. rotation, mapmodel flags)
3.  adjust entities to the new scale as needed
    1.  radii of lights, triggers, sounds etc
    2.  scale of mapmodels, size and lifetime of particles etc
    3.  strength of pushers

4.  remove the old waypoints (/clearwaypoints)
5.  drop new waypoints
6.  tweak lighting settings and entities

