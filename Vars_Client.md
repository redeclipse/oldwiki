''' THIS IS A WORK IN PROGRESS '''

## Vars::Client::A

<b>aboveheadblend</b> <em>O</em>

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
.75

</td>
</tr>
</table>
Determines the opacity of all <b>abovehead\*</b> vars.

<b>aboveheaddamage</b> <em>B</em>

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
B

</td>
<td>
Integer

</td>
<td>
Boolean

</td>
<td>
0 .. 1

</td>
<td>
0

</td>
</tr>
</table>
Shows amount of damage done to a player above their head.

<b>aboveheadeventsize</b> <em>S</em>

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
Float

</td>
<td>
Size

</td>
<td>
0.0 .. 1000.0

</td>
<td>
3.0

</td>
</tr>
</table>
Determines the size of event icons above players' heads.

<b>aboveheadicons</b> <em>S</em>

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
Integer

</td>
<td>
Sum

</td>
<td>
`           `<b>`0`</b>` - none`
`           `<b>`1+`</b>` - damage & kill events`
`           `<b>`2`</b>` - affinity pickups`
`           `<b>`4`</b>` - weapons pickups`
`       `

</td>
<td>
0 .. 7

</td>
<td>
5

</td>
</tr>
</table>
<b>Detemines what type of actions displays icons above player (bitwise OR for affinities and weapons)</b>

<b>aboveheadiconsize</b> <em>S</em>

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
Float

</td>
<td>
Size

</td>
<td>
0.0 .. 1000.0

</td>
<td>
3.0

</td>
</tr>
</table>
Determines the size of icons handled by <b>aboveheadicons</b>.

<b>aboveheadnames</b> <em>B</em>

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
B

</td>
<td>
Integer

</td>
<td>
Boolean

</td>
<td>
0 .. 1

</td>
<td>
1

</td>
</tr>
</table>
Toggles the display of player names above their heads.

<b>aboveheadnamesize</b> <em>S</em>

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
Float

</td>
<td>
Size

</td>
<td>
0.0 .. 1000.0

</td>
<td>
2.0

</td>
</tr>
</table>
Determines the size of names for <b>aboveheadnames</b>.

<b>aboveheadstatus</b> <em>B</em>

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
B

</td>
<td>
Integer

</td>
<td>
Boolean

</td>
<td>
0 .. 1

</td>
<td>
1

</td>
</tr>
</table>
Toggles display of player status above players' heads. Player status is Dominating, Dominated, Death.

<b>aboveheadstatussize</b> <em>S</em>

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
Float

</td>
<td>
Size

</td>
<td>
0.0 .. 1000.0

</td>
<td>
2.0

</td>
</tr>
</table>
Determines the size of player status controlled by <b>aboveheadstatus</b>.

<b>aboveheadteam</b> <em>S</em>

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
Integer

</td>
<td>
Setting

</td>
<td>
`           `<b>`0`</b>` - Do not show`
`           `<b>`1`</b>` - Only teammates`
`           `<b>`2`</b>` - All teams`
`       `

</td>
<td>
0 .. 2

</td>
<td>
2

</td>
</tr>
</table>
Determines how team icons are displayed above player heads.

## Vars::Client::B

<b>bloodsize</b> <em>S</em>

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
Integer

</td>
<td>
Size

</td>
<td>
0 .. 1000

</td>
<td>
50

</td>
</tr>
</table>
Sets the size of blood splatter.

## Vars::Client::C

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
Integer

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
Float

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
Float

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
Integer

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
Integer

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

<b>criticaltex</b> <em>S</em>

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
String

</td>
<td>
Setting

</td>
<td>
N/A

</td>
<td>
textures/critical

</td>
</tr>
</table>
Determines what image is used for the critical hit message.

## Vars::Client::D

<b>dominatetex</b> <em>S</em>

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
String

</td>
<td>
Setting

</td>
<td>
N/A

</td>
<td>
textures/dominate

</td>
</tr>
</table>
Determines what image is used for the "Dominating!" event icon.

<b>dominatedtex</b> <em>S</em>

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
String

</td>
<td>
Setting

</td>
<td>
N/A

</td>
<td>
<grey>textures/dominated

</td>
</tr>
</table>
Determines what image is used for the icon that appears over a player's head while dominating.

<b>dominatingtex</b> <em>S</em>

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
String

</td>
<td>
Setting

</td>
<td>
N/A

</td>
<td>
<grey>textures/dominating

</td>
</tr>
</table>
Determines what image is used for the icon that appears over a player's head while being dominated.

## Vars::Client::E

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
Float

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
Integer

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
Float

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
Float

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

## Vars::Client::F

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
Float

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

## Vars::Client::H

<b>healthbgtex</b> <em>S</em>

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
String

</td>
<td>
Setting

</td>
<td>
N/A

</td>
<td>
<grey>textures/healthbg

</td>
</tr>
</table>
Determines what image is used for the background of the healthbar.

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
Float

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
Integer

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

## Vars::Client::I

<b>inventoryblend</b> <em>O</em>

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
Float

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
Integer

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
Float

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

<b>inventorybgblend</b> <em>O</em>

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
Float

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
Sets the opacity of the Inventory background.

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
Integer

</td>
<td>
Setting

</td>
<td>
`           `<b>`0`</b>` - Do not show at all`
`           `<b>`1`</b>` - Show textual percentage`
`           `<b>`2`</b>` - Show a Bar meter`
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

<b>impulsetex</b> <em>S</em>

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
String

</td>
<td>
Setting

</td>
<td>
N/A

</td>
<td>
<grey>textures/impulse

</td>
</tr>
</table>
Determines what image is used for the Impulse Meter.

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
Float

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
Integer

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
Integer

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

## Vars::Client::N

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
Float

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

## Vars::Client::Z

<b>zoomsensitivity</b> <em>S</em>

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
Float

</td>
<td>
Setting

</td>
<td>
0 .. 1000

</td>
<td>
0.65

</td>
</tr>
</table>
Determines aiming/look sensitivity while zoomed in with the rifle.

<b>zoomtex</b> <em>S</em>

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
String

</td>
<td>
Setting

</td>
<td>
N/A

</td>
<td>
textures/zoom

</td>
</tr>
</table>
Determines what image is used for the scope on the Rifle.
