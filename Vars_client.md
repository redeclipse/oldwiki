In Red Eclipse, all hud elements can be customized via client side variables.

The following list gives only some examples of the many variables related to the user interface.

**NOTE**: This text was taken from an old variables page and should be verified and updated before linking it from other articles.

<b>chatconsize</b> <em>L</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
L

</td>
<td>
integer

</td>
<td>
1.  of Lines
    </td>

<td>
0 .. 100

</td>
<td>
5

</td>
</tr>
</table>
Sets the amount of lines to show in the Chat Console. <b>This does NOT include Overflow lines.</b>

<b>chatconblend</b> <em>O</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
O

</td>
<td>
float

</td>
<td>
Opacity

</td>
<td>
0 .. 1

</td>
<td>
0.75

</td>
</tr>
</table>
Sets the opacity of the Chat Console.

<b>conblend</b> <em>O</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
O

</td>
<td>
float

</td>
<td>
Opacity

</td>
<td>
0 .. 1

</td>
<td>
0.75

</td>
</tr>
</table>
Sets the opacity of the Console. <b>This does NOT include Obituaries and Affinity Events!</b> (Flag, Bomb)

<b>concenter</b> <em>B</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Values

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
B

</td>
<td>
integer

</td>
<td>
Boolean

</td>
<td>
`           `<b>`0`</b>` - Console is in top left`
`           `<b>`1`</b>` - Console is centered`
`       `

</td>
<td>
0 .. 1

</td>
<td>
0

</td>
</tr>
</table>
Toggles alignment of Console.

<b>consize</b> <em>L</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
L

</td>
<td>
integer

</td>
<td>
1.  of Lines
    </td>

<td>
0 .. 100

</td>
<td>
5

</td>
</tr>
</table>
Sets the amount of lines to show in the Console. <b>This does NOT include Overflow lines.</b>

<b>eventblend</b> <em>O</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
O

</td>
<td>
float

</td>
<td>
Opacity

</td>
<td>
0 .. 1

</td>
<td>
1

</td>
</tr>
</table>
Sets the opacity of Event Icons. (First Blood, 2x, 3x, Headshot, etc.)

<b>eventiconfade</b> <em>T</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
T

</td>
<td>
integer

</td>
<td>
Time in Milliseconds

</td>
<td>
500 .. INT\_MAX-1

</td>
<td>
5000

</td>
</tr>
</table>
Sets how long Event Icons should stay on screen.

<b>eventoffset</b> <em>V</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
V

</td>
<td>
float

</td>
<td>
Amount to offset

</td>
<td>
-1 .. 1

</td>
<td>
0.3

</td>
</tr>
</table>
Sets the offset for the Event Icons in your HUD. Negative values move it downward, positive values move it upward.

<b>eventscale</b> <em>S</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
S

</td>
<td>
float

</td>
<td>
Scale Value

</td>
<td>
0.0001 .. 1000

</td>
<td>
2.5

</td>
</tr>
</table>
Sets the scale of Event Icons that appear in your HUD

<b>fullconblend</b> <em>O</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
O

</td>
<td>
float

</td>
<td>
0 .. 1

</td>
<td>
Opacity

</td>
<td>
1

</td>
</tr>
</table>
Sets the opacity of the "Full" Console. This is when the Console is open, and <b>includes Obituaries and Affinity Events.</b> (Flag, Bomb) Excluding those two elements, <b>conblend</b> takes precedence over this variable, yet only affects everything else.

<b>hudblend</b> <em>O</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
O

</td>
<td>
float

</td>
<td>
Opacity

</td>
<td>
0 .. 1

</td>
<td>
1

</td>
</tr>
</table>
Sets the opacity of the entire HUD as a whole. This includes both Consoles, mouse pointer, and Inventory.

<b>hudsize</b> <em>S</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
S

</td>
<td>
integer

</td>
<td>
Size

</td>
<td>
0 .. VAR\_MAX

</td>
<td>
2048

</td>
</tr>
</table>
Sets the size of the entire HUD as a whole. This includes both Consoles, Menus, Inventory, etc.

inventoryblend<b></b> <em>O</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
O

</td>
<td>
float

</td>
<td>
Opacity

</td>
<td>
0 .. 1

</td>
<td>
\`

</td>
</tr>
</table>
Sets the opacity of the Inventory.

<b>inventorycolour</b> <em>S</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Values

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
S

</td>
<td>
integer

</td>
<td>
Setting

</td>
<td>
0 .. 2

</td>
<td>
`           `<b>`0`</b>` - No color at all`
`           `<b>`1`</b>` - Only Weapon icon is colored`
`           `<b>`2`</b>` - Both Weapon icon and slot number are colored`
`       `

</td>
<td>
2

</td>
</tr>
</table>
Toggles the color of the Weapon icons in the Weapon Bar.

<b>inventoryglow</b> <em>S</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
S

</td>
<td>
float

</td>
<td>
Scale Value

</td>
<td>
0 .. 1

</td>
<td>
0.2

</td>
</tr>
</table>
Sets the size of the "glow" in the Inventory. The "glow" is the splatter/explosion image behind Inventory items.

<b>inventoryglowblend</b> <em>O</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
O

</td>
<td>
float

</td>
<td>
Opacity

</td>
<td>
0 .. 1

</td>
<td>
0.75

</td>
</tr>
</table>
Sets the opacity of the "glow" in the Inventory.

<b>inventoryimpulse</b> <em>S</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Values

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
S

</td>
<td>
integer

</td>
<td>
Setting

</td>
<td>
`           `<b>`0`</b>` - Do not show at all`
`           `<b>`1`</b>` - Show only a Ring Meter`
`           `<b>`2`</b>` - Show a Ring Meter with textual percentage`
`       `

</td>
<td>
0 .. 1000

</td>
<td>
2

</td>
</tr>
</table>
Sets how the Impulse Meter is displayed.

<b>inventoryimpulseskew</b> <em>V</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
V

</td>
<td>
float

</td>
<td>
Amount to skew by

</td>
<td>
0.0001 .. 1000

</td>
<td>
0.8

</td>
</tr>
</table>
Sets the size of the ring of the Impulse Meter.

<b>inventorysize</b> <em>S</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
S

</td>
<td>
float

</td>
<td>
Size

</td>
<td>
0 .. 1000

</td>
<td>
0.07

</td>
</tr>
</table>
Sets the size of the Inventory as a whole.

<b>inventorytone</b> <em>S</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Values

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
S

</td>
<td>
integer

</td>
<td>
Setting

</td>
<td>
`           `<b>`0`</b>` - No coloring at all`
`           `<b>`1`</b>` - Uses the color of your Profile Color`
`           `<b>`2`</b>` - Uses Team Color. This includes grey when you are Neutral.`
`           `<b>`3`</b>` - Uses Team Color, but `<b>`only for Team Games.`</b>` When Neutral, your Profile Color is used.`
`           `<b>`4`</b>` - Uses Profile Color, but `<b>`only for Team Games.`</b>` When Neutral, grey will be used.`
`       `

</td>
<td>
0 .. 4

</td>
<td>
2

</td>
</tr>
</table>
Sets the tone of various Inventory elements.

<b>inventoryweapids</b> <em>S</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Values

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
S

</td>
<td>
integer

</td>
<td>
Setting

</td>
<td>
`           `<b>`0`</b>` - Do not show`
`           `<b>`1`</b>` - Do show`
`           `<b>`2`</b>` - `<b><i>`UNKNOWN`</i></b>
`       `

</td>
<td>
0 .. 2

</td>
<td>
1

</td>
</tr>
</table>
Sets how to display the slot number of the Weapons in the Weapon Bar.

<b>noticescale</b> <em>S</em>

<table width="75%" border="1px" cellspacing="3" cellpadding="3">
<tr>
<th>
Parameter

</th>
<th>
Tag Type

</th>
<th>
Description

</th>
<th>
Range

</th>
<th>
Default Value

</th>
</tr>
<tr>
<td>
S

</td>
<td>
float

</td>
<td>
Scale Value

</td>
<td>
0.0001 .. 1000

</td>
<td>
1

</td>
</tr>
</table>
Sets the size of the Notices.
