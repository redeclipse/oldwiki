For Red Eclipse 1.5.8 (Elysium Patch 2)

**Tutorial is not complete; sections are missing.**

### Making a New Map

------------------------------------------------------------------------

After opening Red Eclipse, type

`/edit [name]`

to work on a map. If \[name\] is that of a map (e.g. /edit abuse) then the game will begin an editing session with that map; otherwise, the game will create a new map. Alternatively, after entering an edit session, you can use

`/newmap [size]`

<img src="Edit newmap.png" title="What creating a new map should look like." alt="What creating a new map should look like." width="960" height="520" />

to create a new map with dimensions of 2^\[size\]. Maps default to size 10 (2^10 or 1024 blocks) wide and can only be made larger than that; specifying a size smaller than 10 will default the map size to 10.

After creating a new map, you should be greeted with a blank map that looks like the picture to the right.

To enter edit mode, use the f2 button. You should see black lines outlining right triangles on the surface.

To save the map, use the f8 key while in edit mode.

### The Octree

------------------------------------------------------------------------

Cube 2 is based on an [octree](octree "wikilink") geometry system. An octree separates the world into nesting cubes: cubes may be "pushed" or "pulled" in order to create map geometry. Cubes can then be modified by moving their vertices inward to create nonsquare blocks (more on that later). To begin creating geometry, however, start by selecting a spot on the ground by left clicking it.

<img src="Edit tutorial 2.png" title="Selecting a single cube." alt="Selecting a single cube." width="960" height="520" />

There will now be a white outline around the selected cube (which all but one face of which is underground). Now, to move it, we can use the scroll wheel to "push" and "pull" cubes. You may scroll the cube as far as you wish in order to create a long line of cubes:

<img src="Edit tutorial 3.png" title="Pulling some cubes." alt="Pulling some cubes." width="960" height="520" />

We can then select a different face of one of the cubes we just created and create geometry in a different direction:

<img src="Edit tutorial 4.png" title="Pulling cubes out the side." alt="Pulling cubes out the side." width="960" height="520" />

While this is a workable way to create a level, it would be much faster if we could move a whole bunch of cubes at the same time. Fortunately, we are able to do that by selecting an area of cubes to push and pull. To do this, click one corner of the area you desire to push/pull and hold it until you place the cursor on the opposite diagonal corner of the area you want to select. In this example, you would click on the corner near 1 and then hold it until it is on the 2.

<img src="Edit tutorial 5.png" title="Selecting an area" alt="Selecting an area" width="960" height="520" />

In this example, I pushed the selection downward in order to erase the floor and create a depression. Note how the ground now has more divisions and black lines. This is caused by forcing the engine to divide the floor into more than 4 squares by making it irregularly shaped. To re-optimize the cube layout, use the f4 key in order to do a geometry recalculation ("remip").

<img src="Editing tutorial 6.png" title="Pushing a bunch of cubes" alt="Pushing a bunch of cubes" width="960" height="520" />

Here's what it looks like after a remip. While there are less squares, there are still more than there was before making the depression. This is an unavoidable side effect of the octree geometry system.

<img src="Editing tutorial 7.png" title="Remipping" alt="Remipping" width="960" height="520" />

------------------------------------------------------------------------

As was mentioned earlier, though, the Cube 2 octree allows for nested cubes of different sizes. So far, we have only been working with one size of cube. Using smaller cubes, we can create more detailed structures; with larger ones, we can reduce the system requirements for a large, high geometry map. To change the cube size, press \[g\] and use the scroll wheel. The new cube size will be indicated by the larger or smaller square that follows the cursor. Alternatively, you can press the \[e\] button to enter the editing menu and then \[d\] to enter the options menu. The second-to-bottom slider labeled "grid size" can be changed to change your cube size (larger sizes are bigger cubes).

<img src="Editing tutorial 8.png" title="A bigger brush" alt="A bigger brush" width="960" height="520" />

------------------------------------------------------------------------

As you may have noticed, however, Red Eclipse maps are not exclusively cubes: they have diagonals and slants as well. To do this, select a cube with the middle mouse button (on laptops, this will often be both the left and right mouse buttons simultaneously; on a normal mouse, this will be the scroll wheel) in the corner you would like to push.

<img src="Editing tutorial 9.png" title="Selecting a corner" alt="Selecting a corner" width="960" height="520" />

Notice how the selected corner has itself highlighted within the whole cube being manipulated. Now, to move the face inward, use the scroll wheel to "push" the face inward. Each cube can have each corner pushed inward through 8 levels.

<img src="Editing tutorial 10.png" title="Creating an angle" alt="Creating an angle" width="960" height="520" />

Like how we pushed an area of cubes with the cube brush, we can likewise manipulate cube edges en masse, by instead selecting with the middle mouse button. Be careful not to select an area that perfectly coincides with the current cube grid size, because the editor will interpret that to mean selecting the area normally, leading to entire block pushing like we already have done.

<img src="Editing tutorial 11.png" title="Manipulating multiple cubes" alt="Manipulating multiple cubes" width="960" height="520" />

### Texturing

------------------------------------------------------------------------

While the default cube texture is nice for manipulating geometry with, finishing a map obviously requires a nice paint job. To apply a texture, select an area with the left mouse button and enter the texturing menu with \[F1\]. You will be greeted with a menu with a large list of textures, sorted alphabetically by the author's name.

<img src="Editing tutorial 12.png" title="The texture menu" alt="The texture menu" width="960" height="520" />

To apply a texture to the selected surface, click on the desired texture.

<img src="Editing tutorial 13.png" title="A lovely warning texture" alt="A lovely warning texture" width="960" height="520" />

Now, if you would like to cover the entire cube in a texture, use the \[-\] key to toggle allfaces mode.

<img src="Editing tutorial 14.png" title="Using allfaces on a cube" alt="Using allfaces on a cube" width="960" height="520" />

### Materials

------------------------------------------------------------------------

Red Eclipse can augment the abilities of the Cube 2 octree using materials. Materials are restricted to cube shapes only (cannot be push/pulled like octree cubes) and each have special properties. To access the materials menu, use the **numpad** 0 key. On TKL/laptop keyboards, you may need to use the Fn layer, since the top row 0 key will not work.

You have 10 materials:

<img src="Editing tutorial 15.png" title="Using allfaces on a cube" alt="Using allfaces on a cube" width="960" height="520" />

Starting from bottom left,

`* Light purple: Alpha, makes current selection transparent`
`* Blue: Water, laggy, use sparingly; has four different states`
`* Orange: Lava, kills on contact, needs lighting to look realistic`
`* Red: Noclip, creates an invisible barrier `
`* Green: Clip, overrides octree geometry clipping and lets all players/entities through`
`* Yellow: AIclip, prevents AI from pathing, helps prevent AIs blundering off cliffs/into lava`
`* Black: Death, kills players whose feet enter it`
`* Purple: Ladder, allows players to climb vertically up it`
`* Sky blue: Glass, disrecommended due to alpha generally being more useful; still has some uses with nonsquare windows and geometry within windows`
