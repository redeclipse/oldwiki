Lighting is an entity that can be added to a map in the [editing mode](Editing_Info "wikilink").

## Creating a Light

Creating a spherical light entity: Open the Console with the tilde key (~) or forward slash (/)...

`/newent light 300 180 180 180`

...This will create a light entity with a *radius* of 300 and *Red Green and Blue Values* of 180, or gray.

Once an entity is created, its parameters can be changed by highlighting the Entity, then; pressing the Period Key to enter the desired setting through /entset, or... Holding the corresponding Number Key to the parameter you wish to change while scrolling the Mouse Scroll Wheel.

To move an entity, click the face corresponding to the axis you wish to move it on with the left mouse button and drag.

Once you have created a Light Entity you can create a lightmap texture for your map by using the calclight command

`/calclight `

or press the F7 shortcut key.

If you find that calclight takes too long due to the detail in your map, raise the lightprecision to speed up calculating.

`/lightprecision 256 [1-2048]`

To hide the lightmap and continue editing your map turn on fullbright mode

`/fullbright 1`

or press the shotcut key "B"

To change the base ambient light color for your map (shadow color)use the /ambient command. The default ambient is dark grey

`/ambient 25 25 25`

## Calculating Lightmaps

<table cellspacing="10" style="width:100%">
<tr>
<td width="174">
/fullbright \#

</td>
<td width="219">
toggles the lightmap on/off **Hotkey: B**

</td>
</tr>
<tr>
<td width="174">
/calclight

</td>
<td width="219">
calculates the lightmap (requires at least 1 light in the map) **Hotkey: F7**

</td>
</tr>
<tr>
<td width="174">
/ambient RR GG BB

</td>
<td width="219">
sets the base lighting for the map. Higher values can prevent dark spots that are hard to see while playing at the expense of lighting contrast. Default: 25 25 25 (dark grey) Max: 255 255 255 (equivalent to fullbright)

</td>
</tr>
<tr>
<td width="174">
/lightprecision \#

</td>
<td width="219">
sets the resolution of the lightmap textures contained withing the .mpz map file. This setting greatly affects the size of the map. It is recommended that you raise this setting to keep the number of lightmap textures under 3. Default lightprecision is 32; most maps are between 64 and 256 in lightprecision.

</td>
</tr>
<tr>
<td width="174">
/lightlod \#

</td>
<td width="219">
sets the level of detail for the lightmap. A higher number creates sharper shadows, at the expense of map size. Decreasing lightprecision generally yields better results for the same map file size. Default is 0; max is 10.

</td>
</tr>
<tr>
<td width="174">
/lightthreads \#

</td>
<td width="219">
changes the number of CPU threads to distribute the lightmapping job over. Setting this to the number of cores in the CPU can greatly increase lightmapping performance.

</td>
</tr>
</table>
## Sunlight

Sunlight entities create rays of light that come from a defined angle rather than from a point source. While it is possible to use a conventional light entity in order to simulate global lighting, the edges of the map will have distorted shadows.

To make a sunlight entity, use */newent sunlight \[pitch\] \[red\] \[green\] \[blue\] \[offset\] \[flare\] \[flarescale\]*, or select a sunlight entity from the lighting GUI. For example,

`/newent sunlight 0 255 255 255 20 0 0`

will create white sunlight from straight up with light appearing to radiate from a 20 degree cone.

The most confusing parameter , *offset*, is not provided for in the GUI, nor is it relevant for conventional lights. It controls the spread of the sunlight: higher values will make the sunlight appear to come from a larger area. Setting *offset* to -1 will make the sunlight appear to come from a point.

## Lightfx

Lightfx entities can be linked to lights to allow for more interesting effects than conventional lights. Lightfx entities can be configured in a few modes: spotlight, dynlight, flicker, pulse, and glow.

To create a lightfx, use

`/newent lightfx`

Setting the *type* parameter to 0 (default) will put the lightfx entity into spotlight mode. When linked to a light, it will only allow the light entity to shine in the direction indicated by a cone radiating from the light entity. Changing the *mod* parameter will affect the spread of the light cone: higher values will create a larger cone. When using a spotlight, it is often necessary to create another light entity to create diffuse light around the light source, since the spotlight will now only shine in the direction indicated.

Setting the *type* parameter to 1 will put the lightfx entity into dynlight mode. Red Eclipse's default lighting method is static, using lightmaps to paint textures with a fixed lighting value. Dynamic lighting is done in real time, allowing moving entities to affect it; however, its implementation is suboptimal and should be used sparingly.

Setting the *type* parameter to 2 will put the lightfx entity into flicker mode. Flicker uses a dynamic light (which carries all the caveats of dynamic lighting), allowing the creation of a light entity that will flicker on and off. This is useful for simulating things such as failing lights, blinking indicators, or even lightning (especially when timed with the corresponding sound). Setting the *rnd-min* and *rnd-max* flags from the entity GUI can allow for random flickering. Changing *mod* changes the spacing between flickers.

Setting the *type* parameter to 3 will put the lightfx entity into pulse mode. Like flicker, pulse is a dynamic light, which instead of sharply turning on and off, pulses more smoothly between off and on. Like flicker, pulse also can be manipulated by the *mod*, *rnd-min* and *rnd-max* flags.

Lastly, setting the *type* parameter to 4 will put the lightfx entity into glow mode. Glow creates an effect similar to dynlight, but with more opacity. Like dynlights, glow should be used sparingly.

## Lighting Tips

-   Lights should come with accompanying geometry or mapmodels, i.e. put light entities near physical lights.
-   Lighting should be used to make textures more vibrant: create some contrast, without using too many clashing colors.
-   Large lights will take less time and less disk space than using more small lights to cover the same area.
-   Try to use as high of a lightprecision as reasonable: this saves disk space and reduces rendering times.
-   To keep lightprecision high, change the blurr value to 1 or 2 to un-pixelize the shadow lines.
-   While dark areas may look good, the primary purpose of a map is to be played. Consider adding more lighting to make things visible.
-   Implied sunlight may work as a global lighting option, manually adding sunlights often provides a better match to the skybox.
-   Having high ambient lighting reduces the contrast of light entities. Use light entities liberally instead of raising the ambient.

