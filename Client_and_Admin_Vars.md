This page was automatically generated from the source of Red Eclipse, please do not edit it manually.

<table style="border:1px solid #000000; width:100%;">
<tr>
<th>
Name & Parameters

</th>
<th>
Description

</th>
<th>
Type

</th>
<th>
Default Value

</th>
<th>
Range

</th>
<th>
Identifier Flags

</th>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>actorscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
defines the size of all actors (players, bots, grunts, etc.)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>aiinitdelay</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>ailongdelay</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
10000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>aircoastscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiply aircoast by this much

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>airefreshdelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
delay imposed before the AI manager reorganises their setup

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>allowlock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines who may allow players; 0 = helper, 1 = supporter, 2 = moderator, 3 = operator, 4 = administrator, 5 = developer, 6 = creator, 7 = nobody

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>allowmaps</b> <i>&lt;list&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines which maps are allowed to be chosen without elevated privileges

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
ares bath battlefield biolytic bloodlust canals cargo center colony conflict cutec cyanide darkness deadsimple deathtrap deli depot dropzone dutility echo erosion error forge foundation fourplex futuresport ghost hawk hinder institute keystone2k linear livefire longestyard mist neodrive nova oneiroi panic processing pumpstation purge spacetech starlibido stone suspended testchamber tower tranquility tribal ubik vault venus warp wet

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>assistkilldelay</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>autoadmin</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines if authorities claim status by default

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>autospecdelay</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
60000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>autospectate</b> <i>&lt;bool&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines when the game switches automatically to speactate mode; 0 = when idle, 1 = when remaining dead for autospecdelay

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>balancedelay</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
10000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..30000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>balancemaps</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
-1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
-1..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>balancenospawn</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>banlock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines who may ban players; 0 = helper, 1 = supporter, 2 = moderator, 3 = operator, 4 = administrator, 5 = developer, 6 = creator, 7 = nobody

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bleeddamage</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
amount of damage bleeding deals

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bleeddelay</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds for which bleeding deals damage

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bleedtime</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time in milliseconds bleeding lasts for, try to allow an extra 500ms breathing room for sync

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5500

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberbuffarea</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiply affinity radius by this much for buff

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
128.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberbuffdamage</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiply outgoing damage by this much when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberbuffdelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
buffed for this long after leaving

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberbuffing</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
buffed; 0 = off, &1 = when guarding, &2 = when securing

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberbuffshield</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
divide incoming damage by this much when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bombercarryspeed</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
scales the movement speed of the player carrying the bomber ball by this value

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.9

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bombercarrytime</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds a player can carry the bomber ball before it explodes

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
15000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bombercollide</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
64

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberdelay</b> <i>&lt;millisecond&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
delay before spawning in bomber

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberdelta</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberelasticity</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
-1000000.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberextinguish</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
6

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberholdinterval</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds a player needs to hold the ball in hold bomber-ball to get a point

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberholdlimit</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
finish when score is this or more (hold)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberholdpenalty</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
penalty for holding too long

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
10

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberholdpoints</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
points added to score

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberholdtime</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
15000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberinteracts</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberlimit</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
finish when score is this or more (non-hold)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberlockondelay</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
250

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bombermaps</b> <i>&lt;list&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
bomber-ball maps

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
ares battlefield biolytic canals cargo center colony conflict cutec darkness deadsimple deli depot dropzone dutility echo erosion foundation fourplex futuresport ghost linear mist nova pumpstation stone suspended tower tribal vault venus warp wet

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberminspeed</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
50.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberpenalty</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
points taken from score

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberpickupdelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time in milliseconds a player needs to wait to be able to pick up the bomber ball again after dropping it

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberpickuppoints</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
points added to score

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberpoints</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
points added to score

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberregenbuff</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0 = off, 1 = modify regeneration when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberregendelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
regen this often when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberregenextra</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
add this to regen when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberrelativity</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.25

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberresetdelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds before the bomber ball resets after being dropped

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
15000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberspeed</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
speed at which the bomber ball moves when thrown or dropped; for reference, 100 is the speed the player moves at by default

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
200.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberthreshold</b> <i>&lt;distance&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
automatically drop the bomb if the bomb-carrier "warps" more than this distance

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bomberwaterfric</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.75

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-1000000.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomberweight</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
200.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
-1000000.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>botbalance</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines bot balancing method; -1 = always use numplayers, 0 = don't balance, 1 or more = fill only with this\*numteams

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>botfemalenames</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
sue debbie luanne brandy angel kitty jane ava brianna chloe destiny emma faith grace hannah julia kaylee lily madison natalie olivia peyton riley sophia taylor unique victoria ximena yaretzi zoe avdotya aurora agatha agafya agnes ada adelaide adeline adele adriana aksinya alevtina alain alina alice aliyah alla alsou alba albina alfia alya amalia amin amir anahit anastasia angelina angela angelica anisa anna antonina anfisa arina bela bertha valentine valeria varvara vasilisa veronica victoria vilena violet vita vitalina galina ghalia greta gulmira dana daniela dara darina daria jamila diana dilara dinara eve eugene evdokia catherine helena elizabeth yesenia jeanne jasmine josephine zaire zamira zara sarin zemfira zinaida zoe zulfiya zukhra ilona inga inessa inna john ira iraida irene irma kamila camilla karina caroline kira claudia clara bark cornelia christina xenia lada lana larissa laura leila lera lesya liana lika lillian lily lina linda liora lyra laura ludmila magdalena mara margaret marianne marika maria martha mika milena milica monica naila naima naomi natalia nelly nick nicole nina ninel nora nuria oksana olesya olga peacock paula pelagia platonida pauline praskovya rada razin raisa regina mignonette rena renata rihanna rina rita rogneda rose rusalina sabrina sandra sarah sati safura svetlana seraphim sylvia snezana sophia stella stephanie susanna taisa tamara tara teresa tina ulyana ursula feruza firouz flora florentina florian shakira sheila shelley evelina evita eleanor eliana eliza elina ella elvina elmira elnara emma ermina ethel eter julia jadwiga jana yanina yasmin yaroslav jasmina

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>botfemalevanities</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
badge

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>botlimit</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
maximum number of bots allowed, regardless of any other variable/setting

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
32

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>botmalenames</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
moe larry curly jerry ted phil bob billy joe john james gunner dante dick lorenzo chuck zeus alexander benjamin daniel ethan fernando gabriel hunter isaac jacob kevin logan michael noah owen parker ryan samuel tyler uriel victor william xavier yahir zachary abram avaz abraham agap agapit agathon adam adrian azamat azat aidar airat akim alan alexander alex ali alikhan diamond albert anatoly angel andrew anton anfim aram arkady arman armen arseniy arslan artem artemia arthur askhana ahmet ashot bahram bogdan boris borislav bronislaw damask vadim valentine valery waldemar vardan vasily victor william wit vitali vladimir vladislav vladlen vsevolod vyacheslav hamlet harry gennady henry henry george gerasim herman hermann gleb gordi gregory gustav david dawlat damir dana daniel danislav denis jamal james jeremy jeremiah joseph dick dinar dino dmitry dobrynya eugene evdokim eustace yegor elisha emelyan jeremiah yefim ephraim zhdan zakir zachar zinovy ibrahim ivan ignat ignatius igor jerome ilshat ilya innocent isaac isaac isidore iskander ismail kazbek camille karen karim charles kim cyril klaus klim conrad constantine cornelius kuzma leo leon leonard leonid leopold luke lukillian lukjan lubomir ludwig louis lucius michael makar macarius maxim maximilian maqsood mansour march marat mark marseilles martin matthew mahmoud mika mikula miron miroslav michael mstislav murat mohammed nazar nikita nicodemus nicola nicholas nils oleg orlando oscar ostap paul pedro peter plato prokhor ravil radium radik radomir radoslav razil raymond ramiz ramil ramon ranelagh ratmir raphael richard robert rodion roland rostislav rudolph ruslan rustam ray sawa savely samuel svyatoslav sebastian sergei stepan tamerlan taras fedor felix philip fred frederick shamil charles edgar edward eldar julian julius yuri jacob yaroslav

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>botmalevanities</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
badge

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>botoffset</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
increases or decreases the amount of bots starting from the numplayers value of the current map

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-2147483647..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>botscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
scale the 'numplayers' world variable which determines bot auto population

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>botskillmax</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
maximum randomly assigned AI skill level

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
75

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1..101

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>botskillmin</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
minimum randomly assigned AI skill level

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
60

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..101

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>botspeed</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>burndamage</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
amount of damage fire burning deals

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>burndelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time in milliseconds for which fire burning deals damage

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>burntime</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds fire burns for, try to allow an extra 500ms breathing room for sync

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
5500

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>capturebuffarea</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiply affinity radius by this much for buff

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
96.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>capturebuffdamage</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiply outgoing damage by this much when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>capturebuffdelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
buffed when guarding, and for this long after

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>capturebuffing</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
buffed; 0 = off, &1 = when guarding/secured, &2 = when carrying enemy, &4 = also defending secured, &8 = also defending enemy carrier

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..15

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>capturebuffshield</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
divide incoming damage by this much when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>capturecarryspeed</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.9

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>capturecollide</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
64

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>capturedefenddelay</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
15000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>captureelasticity</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-1000000.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>captureextinguish</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
6

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>captureinteracts</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>capturelimit</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
number of captures required to end the round (and win) in ctf

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>capturemaps</b> <i>&lt;list&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
capture-the-flag maps

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
ares bath battlefield biolytic canals cargo center colony conflict cutec darkness deadsimple deli depot dropzone dutility echo erosion foundation fourplex futuresport ghost institute keystone2k linear mist nova panic pumpstation stone suspended tribal vault venus warp wet

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>captureminspeed</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>capturepickupdelay</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>capturepickuppoints</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
points added to score

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>capturepoints</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
points added to score

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>captureprotectdelay</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
15000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>captureregenbuff</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0 = off, 1 = modify regeneration when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>captureregendelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
regen this often when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>captureregenextra</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
add this to regen when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>capturerelativity</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.25

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>capturerepelspeed</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
25.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>capturerepulsion</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
16.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>captureresetdelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time in milliseconds before a dropped flag automatically resets

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
30000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>capturethreshold</b> <i>&lt;distance&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
automatically drop the flag if the flag-carrier "warps" more than this distance

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>capturewaterfric</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.75

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-1000000.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>captureweight</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
200.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
-1000000.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>connectlock</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>coopbalance</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>coopmultibalance</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiply number of players in bot teams by this much

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>coopskillmax</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
85

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..101

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>coopskillmin</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
75

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1..101

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>damagescale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
scale damage by this amount

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>deadpushscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
scale hit pushes by this amount when it results in a frag

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>deadstunscale</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>defaultmap</b> <i>&lt;map&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
default map, "" = random

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>defaultmode</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
default game mode; 1 = editing, 2 = deathmatch, 3 = ctf, 4 = dtf, 5 = bomber, 6 = trial

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>defaultmuts</b> <i>&lt;sum&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
default mutators, convenient to set using a sum of $mutsbit\* vars (available: multi, team, coop, instagib, medieval, ballistic, duel, survivor, arena, onslaught, jetpack, vampire, expert, resize, gsp1 = first mode variation {ctf-return, dtf-quick, bomber-hold}, gsp2 = second mode variation {ctf-defend, dtf-conquer}, gsp3 = third mode variation {ctf-protect, dtf-king-of-the-hill}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..131071

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>defendbuffarea</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiply affinity radius by this much for buff

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
64.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>defendbuffdamage</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiply outgoing damage by this much when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>defendbuffdelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
buffed for this long after leaving

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>defendbuffing</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
buffed; 0 = off, &1 = when guarding, &2 = when securing, &4 = even when enemies are present

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>defendbuffoccupy</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
for defendbuffing&4, must be occupied this much before passing

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>defendbuffshield</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
divide incoming damage by this much when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>defendflags</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
flags to init and how; 0 = init all (neutral), 1 = init neutral and team only, 2 = init team only, 3 = init all (team + neutral + converted)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>defendinterval</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
50

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>defendking</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
points needed to occupy in king-of-the-hill

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
25

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>defendlimit</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines the style of dtf play; number of points required to end the round (and win) in dtf

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>defendmaps</b> <i>&lt;list&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
defend-the-flag maps

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
ares bath battlefield biolytic canals cargo center colony conflict cutec darkness deadsimple deli depot dropzone dutility echo erosion foundation fourplex futuresport ghost institute keystone2k linear livefire mist nova panic processing pumpstation stone suspended tower tribal ubik vault venus warp wet

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>defendoccupy</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
points needed to occupy in regular games

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
100

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>defendpoints</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
number of points given in dtf

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>defendregenbuff</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0 = off, 1 = modify regeneration when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>defendregendelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
regen this often when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>defendregenextra</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
add this to regen when buffed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>demoautorec</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines if demos are automatically recorded each match

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>democount</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines the maximum amount of demo files that may be saved simultaneously on the server (deletes old demos if exceeded)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>demokeep</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>demolock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines who may record demos; 0 = helper, 1 = supporter, 2 = moderator, 3 = operator, 4 = administrator, 5 = developer, 6 = creator, 7 = nobody

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>demomaxsize</b> <i>&lt;kilobytes&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines the maximum size of individual demo files that may be saved on the server

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
16

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>dominatecount</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
number of frags on a single player without revenge before it is considered domination

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>dominatepoints</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>duelclear</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines if items are reset at the end of each round

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>duelcycle</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines if players are force-cycled after a certain number of wins (bit: 0 = off, 1 = non-team games, 2 = team games)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>duelcycles</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
maximum wins in a row before force-cycling (0 = num team/total players)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>duellimit</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds before next round in duel/survivor

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
5000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>duelmaps</b> <i>&lt;list&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
duel map filter (extra filter on top of mode filter)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
bath bloodlust darkness deadsimple dutility echo fourplex ghost longestyard livefire stone panic vault wet

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>duelprotect</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds after spawning players cannot be damaged in duel/survivor matches

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
5000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>duelreset</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
reset winner in duel

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>duelwarmup</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
15000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>editlock</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>enemybalance</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiply number of enemy spawns by this much

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>enemybonus</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>enemylimit</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
32

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>enemyscale</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>enemyskillmax</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
80

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..101

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>enemyskillmin</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
65

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1..101

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>enemyspawndelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determine length of time after map start enemies first spawn

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>enemyspawndistmax</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
512.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>enemyspawndistmin</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
32.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>enemyspawnstyle</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines enemy spawning style, 0 = all at once, 1 = staggered, 2 = random, 3 = randomise between both

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>enemyspawntime</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determine length of time before enemies respawn

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
30000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>enemyspeed</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>enemystrength</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
scale enemy health values by this much

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>firstbloodpoints</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>floodlines</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
number of lines in floodtime span before too many

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>floodlock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
enables flood protection for everyone below a specific privilege level; 0 = disable flood protection, 1 = helper, 2 = supporter, 3 = moderator, 4 = operator, 5 = administrator, 6 = developer, 7 = creator, 8 = everyone

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>floodmute</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
automatically mute player when warned this many times

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>floodtime</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time span to check for floody messages

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
10000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
250..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>floorcoastscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiply floorcoast by this much

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>fragbonus</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>gamepaused</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
pauses the game, automatically unset by server

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>gamespeed</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
override gameplay speed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
100

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1..10000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>gamespeedlock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines if gamespeed is locked (also limited by varslock); 0 = off, 1 = helper, 2 = supporter, 3 = moderator, 4 = operator, 5 = administrator, 6 = developer, 7 = creator, 8 = nobody

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>gauntletbuffarea</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
256.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>gauntletbuffdamage</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>gauntletbuffdelay</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>gauntletbuffing</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>gauntletbuffshield</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>gauntletghost</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>gauntletmaps</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
ares bath battlefield biolytic canals cargo center colony conflict deli depot dropzone erosion foundation futuresport ghost linear nova stone suspended tribal venus wet

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>gauntletregenbuff</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>gauntletregendelay</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>gauntletregenextra</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>gauntletweapon</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..10

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>gravityscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiply gravity by this much

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>headshotpoints</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>hitpushscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
scale hit pushes by this amount

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>hitstunscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiply "stun target on hit" by this amount

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>holdmaps</b> <i>&lt;list&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
hold bomber-ball maps

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
ares bath battlefield biolytic canals cargo center colony conflict cutec darkness deadsimple deli depot dropzone dutility echo erosion foundation fourplex futuresport ghost keystone2k linear mist nova panic processing pumpstation stone suspended tower tribal ubik vault venus warp wet

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulseallowed</b> <i>&lt;sum&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines which impulse actions are allowed (bitwise OR); 0 = off, 1 = dash, 2 = boost, 4 = pacing, 8 = parkour

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
15

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..15

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulseboost</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiplier of impulse when just boosting

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulsecost</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
cost of impulse jump

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulsecostrelax</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
8

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..15

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulsecostscale</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulsecount</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
number of impulse actions per air transit

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
6

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulsedash</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiplier of impulse when dashing

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulsedashdelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
minimum time between dashes/powerslides

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulsedelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
minimum time between boosts

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
250

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulsejet</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
jetpack impulse meter depletion

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulsejump</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiplier of impulse when jumping

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulsekickdelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
minimum time between wall kicks/climbs

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
350

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulselimit</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
maximum impulse speed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulsemelee</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiplier of impulse when using melee

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.75

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulsemeter</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
impulse dash length; 0 = unlimited, anything else = timer

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
30000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulsepacing</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
pacing counts toward impulse; 0 = off, anything else = multiplier of time

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulseparkour</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiplier of impulse when doing other parkour

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulseparkourkick</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
parkour kick modifier

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulseparkournorm</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
minimum parkour surface z normal

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulseparkourvault</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
parkour vault modifier

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulsepower</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
power jump modifier

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulseregen</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
impulse regen multiplier

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
5.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulseregencrouch</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
impulse regen modifier when crouching

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulseregendelay</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
delay before impulse regens

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
350

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulseregeninair</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
impulse regen modifier when in air

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.75

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulseregenjet</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
impulse regen jetpack modifier

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulseregenjetdelay</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
delay before impulse regens after jetting, -1 = must touch ground

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulseregenmove</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
impulse regen modifier when moving

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulseregenpacing</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
impulse regen modifier when pacing

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.75

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulseregenslide</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulseskate</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
length of time a run along a wall can last

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulseslide</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time before powerslides end

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulseslip</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time before floor friction kicks back in

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
250

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulsespeed</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
extra velocity to add when impulsing

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
90.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulsespread</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiply projectile spread by this much when impulsing/pacing/jetpacking

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulsestyle</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
impulse style; 0 = off, 1 = touch and count, 2 = count only, 3 = freestyle

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>impulsevaultmax</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
maximum percentage of height for vault

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>impulsevaultmin</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
minimum percentage of height for vault

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.25

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>inairspread</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiply projectile spread by this much when jumping/in-air

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>instadelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds before players can respawn in instagib mutated modes

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>instaprotect</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time in milliseconds after spawning players cannot be damaged in instagib matches

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
3000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>instaresizeamt</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
each kill adds this much size in insta-resize

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>instaweapon</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
weapon players spawn with in instagib, defaults to rifle (7)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..10

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>intermlimit</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds intermission lasts

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
15000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>itemcollide</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
64

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>itemelasticity</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
-1000000.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>itemextinguish</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
6

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>iteminteracts</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>itemminspeed</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>itemrelativity</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
-1000000.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>itemrepelspeed</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
25.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>itemrepulsion</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
8.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>itemsallowed</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines if items are present in the level; 0 = never, 1 = all but instagib, 2 = always

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>itemspawndelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds after map start items first spawn

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>itemspawnstyle</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines the timing of item spawning at map start; 0 = all at once, 1 = staggered, 2 = random, 3 = randomise between both

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>itemspawntime</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds before items (re)spawn

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
15000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>itemthreshold</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
if numitems/(players\*maxcarry) is less than this, spawn one of this type

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>itemwaterfric</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.75

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>itemweight</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
150.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-1000000.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>jetdecay</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
decay rate of one unit per this many ms

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
15.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>jetdelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
minimum time between jetpack

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
250

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>jetheight</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
jetpack maximum height off ground

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>jetpackmaps</b> <i>&lt;list&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
jetpack map filter (extra filter on top of mode filter)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
ares battlefield biolytic canals cargo center colony conflict cutec darkness deadsimple deathtrap deli depot dropzone dutility echo erosion error forge fourplex futuresport ghost linear longestyard mist nova oneiroi pumpstation spacetech starlibido suspended testchamber tower tranquility tribal ubik venus warp

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>jumpspeed</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
extra velocity to add when jumping

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
110.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>kamikaze</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines the level of kamikaze events; 0 = never, 1 = holding grenade, 2 = have grenade, 3 = always

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>kicklock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines who may kick players; 0 = helper, 1 = supporter, 2 = moderator, 3 = operator, 4 = administrator, 5 = developer, 6 = creator, 7 = nobody

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>kickpushcrouch</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiply kick pushes from weapons by this much when crouching

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>kickpushscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiply kick pushes from weapons by this much

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>kickpushsway</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiply kick push effect on hud gun sway by this much

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0125

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>kickpushzoom</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiply kick pushes from weapons by this much when zoomed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.125

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>kingmaps</b> <i>&lt;list&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
king-of-the-hill maps

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
ares bath battlefield biolytic canals cargo center colony conflict darkness deadsimple depot dutility echo fourplex linear livefire processing stone suspended tower tribal ubik vault venus

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>largemaps</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
ares battlefield biolytic canals cargo center colony cutec deadsimple deathtrap deli depot erosion forge foundation futuresport ghost linear mist nova processing pumpstation spacetech suspended tower tranquility tribal ubik venus warp

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>limitlock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines who may limit players; 0 = helper, 1 = supporter, 2 = moderator, 3 = operator, 4 = administrator, 5 = developer, 6 = creator, 7 = nobody

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>liquidcoastscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiply liquidcoast by this much

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>liquidextinguishscale</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>liquidspeedscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiply liquidspeed by this much

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>liquidsubmergescale</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mainmaps</b> <i>&lt;list&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
deathmatch maps

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
ares bath battlefield biolytic bloodlust canals cargo center colony conflict cutec darkness deadsimple deathtrap deli depot dropzone dutility echo erosion error foundation fourplex futuresport ghost institute keystone2k linear livefire longestyard mist nova oneiroi panic processing pumpstation spacetech starlibido stone suspended tower tribal ubik vault venus warp wet

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>maphistory</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
remember this many maps that can't be voted again if votelock is set

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mapsfilter</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0 = off, 1 = filter based on mutators, 2 = also filter based on players

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>mapslock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines at which privilege level maps are locked, accordigng to mapslocktype; 0 = off, 1 = helper, 2 = supporter, 3 = moderator, 4 = operator, 5 = administrator, 6 = developer, 7 = creator, 8 = nobody

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mapslocktype</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines the maps locking type; 0 = off, 1 = lock level only, 2 = lock level can select non-rotation

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>masterlock</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>maxalive</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
only allow this\*numplayers (for current map) to be alive at once

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>maxaliveminimum</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
only enables maxalive limit if the number of players is more than or equal to this

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>maxalivequeue</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
toggle queue system (used if number of players exceeds maxalive\*numplayers for current map); 0 = prohibits leaving spectator, 1 = players enter queue

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>maxalivethreshold</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
only enables maxalive limit if the number of players is more than or equal to this\*numplayers (for current map)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>maxcarry</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
maximum number of weapons a player can carry, plus pistol and grenades

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..6

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>maxhealth</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
spawnhealth \* maxhealth defines the maximum amount of health that can be reached (e.g. standing next to a friendly goal)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>maxhealthvampire</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
spawnhealth \* maxhealthvampire defines the maximum amount of health that can be reached by damaging other players in vampire

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>maxresizescale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
defines the largest scaled size a player can become in a match with the resize mutator enabled

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mediummapmax</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
maximum number of players for a medium map

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
12

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>mediummaps</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
ares battlefield biolytic canals cargo center colony conflict cutec darkness deadsimple deathtrap deli dropzone echo erosion error forge foundation fourplex futuresport ghost institute keystone2k linear livefire mist nova oneiroi panic processing pumpstation spacetech suspended starlibido stone tower tranquility tribal ubik venus warp wet

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>messagelength</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
128

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
32..511

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>messagelock</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>minresizescale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
defines the smallest scaled size a player can become in a match with the resize mutator enabled

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>modelock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines at which privilege level modes are locked, according to modelocktype; 0 = off, 1 = helper, 2 = supporter, 3 = moderator, 4 = operator, 5 = administrator, 6 = developer, 7 = creator, 8 = nobody

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>modelockfilter</b> <i>&lt;sum&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines the modes which are allowed to be used as dictated by modelock, convenient to set using a sum of $modebit\* vars (available: editing, deathmatch, capture, defend, bomber, trial), example: (+ $modebitediting $modebitdeathmatch)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
188

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..255

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>modelocktype</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines the mode locking type; 0 = off, 1 = lock level only, 2 = lock level can set limited mode and higher

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>movecrawl</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiplier of speed when crawling

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.6

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>moveinair</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiplier of speed when in-air

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.9

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>movejet</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiplier of speed when using jetpack

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.6

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>movepacing</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiplier of speed when pacing

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.6

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>movespeed</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
baseline movement speed

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
100.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>movespread</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiply projectile spread by this much when moving

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>movestepdown</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiplier of speed when stepping down

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.15

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>movestepup</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiplier of speed when stepping up

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.95

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>movestrafe</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiplier of speed when strafing

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>movestraight</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiplier of speed when only moving forward

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1e-06..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>multikillbonus</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>multikilldelay</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time in milliseconds multiple kills in a row must occur

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>multikillpoints</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>multimaps</b> <i>&lt;list&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
maps allowed for modes which \*require\* multi spawns (ctf/bb)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
canals deadsimple depot keystone2k warp fourplex

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mutelock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines who may mute players; 0 = helper, 1 = supporter, 2 = moderator, 3 = operator, 4 = administrator, 5 = developer, 6 = creator, 7 = nobody

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>mutslockfilter</b> <i>&lt;sum&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines the mutators which are allowed to be used as dictated by modelock, convenient to set using a sum of $mutsbit\* vars (available: multi, team, coop, instagib, medieval, kaboom, duel, survivor, classic, onslaught, jetpack, vampire, expert, resize, gsp1 = first mode variation {ctf-return, dtf-quick, bomber-hold}, gsp2 = second mode variation {ctf-defend, dtf-conquer}, gsp3 = third mode variation {ctf-protect, dtf-king-of-the-hill}), example: (+ $mutsbitmulti $mutsbitteam)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
126975

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..131071

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>overtimeallow</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
if scores are equal, go into overtime

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>overtimelimit</b> <i>&lt;minutes&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
maximum time overtime may last, 0 = forever

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>pointlimit</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
number of points required to end the round (and win) in deathmatch modes

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>previousmaps</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
list of previously played maps

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_READONLY IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>pushlimited</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.75

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>pushscale</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>quakefade</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
250

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>quakelimit</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
200

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>quakewobble</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
18

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>radiallimited</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiply explosion radius by this amount in limited situations (eg. instagib)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.75

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>radialscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiply explosion radius by this amount

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>regendecay</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
if over maxhealth, decay this amount each regen

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>regendelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds after being damage before normal regeneration resumes

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>regenhealth</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
amount of health regneration gives

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>regentime</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds for which regenerate gives health

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>resetallowsonend</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines when the allow list is reset; 0 = off, 1 = just when empty, 2 = when matches end

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>resetbansonend</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines when the ban list is reset; 0 = off, 1 = just when empty, 2 = when matches end

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>resetlimitsonend</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines when the limit list is reset; 0 = off, 1 = just when empty, 2 = when matches end

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>resetmmonend</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines when privilege mode changes are reset; 0 = off, 1 = just when empty, 2 = when matches end

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>resetmutesonend</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines when the mute list is reset; 0 = off, 1 = just when empty, 2 = when matches end

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>resetvarsonend</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines when these game variables are reset; 0 = off, 1 = just when empty, 2 = when matches end

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>revengepoints</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>rotatemaps</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines behaviour of map rotation; 0 = off, 1 = sequence, 2 = random

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>rotatemapsfilter</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0 = off, 1 = filter based on mutators, 2 = also filter based on players

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>rotatemode</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines if modes rotate when the server selects the next map

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>rotatemodefilter</b> <i>&lt;sum&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines the modes which can be selected when the server selects the next map, convenient to set using a sum of $modebit\* vars (available: editing, deathmatch, capture, defend, bomber, trial), example: (+ $modebitediting $modebitdeathmatch)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
188

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..255

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>rotatemuts</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines if mutators rotate when the server selects the next map (more than 1 decreases chances)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>rotatemutsfilter</b> <i>&lt;sum&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines the mutators which can be selected when the server selects the next map, convenient to set using a sum of $mutsbit\* vars (available: multi, team, coop, instagib, medieval, kaboom, duel, survivor, classic, onslaught, jetpack, vampire, expert, resize, gsp1 = first mode variation {ctf-return, dtf-quick, bomber-hold}, gsp2 = second mode variation {ctf-defend, dtf-conquer}, gsp3 = third mode variation {ctf-protect, dtf-king-of-the-hill}, example: (+ $mutsbitmulti $mutsbitteam)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
126399

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..131071

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>selfdamage</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines if the player can damage themselves; 0 = off, 1 = either hurt self or use teamdamage rules

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>selfdamagescale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines how much self-damage is dealt; 0 = off, anything else = scale for damage

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-1000000.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>serverclients</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
maximum number of allowed clients

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
16

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..256

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>serverdebug</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>serverdesc</b> <i>&lt;text&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
server description

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>servermotd</b> <i>&lt;text&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
server message of the day

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>serveropen</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines server openness for public use; 0 = allow "setpriv 1" and locked/private, 1 = allow "setpriv 1" but no privileged mode, no locked/private, 2 = allow "setpriv 1" but disallows private privileged mode (for public coop-editing), 3 = privilege only by moderator or above

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>shockdamage</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>shockdelay</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>shockstunfall</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>shockstunscale</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>shockstuntime</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>shocktime</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
5500

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>slidecoastscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
multiply slidecoast by this much

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>smallmapmax</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
maximum number of players for a small map

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
6

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>smallmaps</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
bath bloodlust darkness deadsimple dutility echo error fourplex ghost longestyard livefire stone panic vault wet

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>spawnarmour</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>spawndelay</b> <i>&lt;millisecond&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time in milliseconds before players can respawn in most modes

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>spawngrenades</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
spawn with grenades; 0 = never, 1 = all but instagib/time-trial, 2 = always

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>spawnhealth</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
defines the amount of health you spawn with, and the maximum amount of health to which you will regenerate when damaged, assigning this variable a value of 0 or 1 will cause you to die in one hit

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
100

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>spawnmines</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>spawnprotect</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time in milliseconds after spawning players cannot be damaged

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
3000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>spawnrotate</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
spawn point rotation; 0 = let client decide, 1 = sequence, 2 = random

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>spawnweapon</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
weapon players spawn with, defaults to pistol (1)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..10

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>speclock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines who may force players to spectate; 0 = helper, 1 = supporter, 2 = moderator, 3 = operator, 4 = administrator, 5 = developer, 6 = creator, 7 = nobody

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>spreebreaker</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>spreecount</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
number of consecutive frags for each spree level

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>spreepoints</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>stillspread</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multiply projectile spread by this much when standing still

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>stunlimited</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.75

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>stunscale</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>teamalphacolour</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0x5F66FF

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0x000000..0xFFFFFF

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_HEX

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>teamalphaname</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
alpha

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>teambalance</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines the method of team balancing; 0 = off, 1 = by number then rank, 2 = by rank then number

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>teamdamage</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines if the player can damage team members; 0 = off, 1 = non-bots damage team, 2 = all players damage team

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>teamdamagescale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines how much team damage is dealt; 0 = off, anything else = scale for damage

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-1000000.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>teamenemycolour</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0xF88820

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0x000000..0xFFFFFF

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_HEX

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>teamenemyname</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
enemy

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>teamkappacolour</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0xFFD022

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0x000000..0xFFFFFF

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_HEX

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>teamkappaname</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
kappa

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>teamkillban</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>teamkillkick</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>teamkilllock</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>teamkillpenalty</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>teamkillrestore</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>teamkilltime</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>teamkillwarn</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>teamneutralcolour</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0x90A090

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0x000000..0xFFFFFF

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_HEX

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>teamneutralname</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
neutral

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>teamomegacolour</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0xFF4F44

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0x000000..0xFFFFFF

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_HEX

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>teamomeganame</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
omega

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>teampersist</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0 = off, 1 = only attempt, 2 = forced

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>teamsigmacolour</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0x22FF22

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0x000000..0xFFFFFF

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_HEX

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>teamsigmaname</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
sigma

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>timelimit</b> <i>&lt;minutes&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in minutes before round ends; 0 = off

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
10

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>trialdelay</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time in milliseconds before players can respawn in trial mode

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
500

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>trialghost</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>trialmaps</b> <i>&lt;list&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time-trial maps

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
cyanide hawk hinder neodrive purge testchamber

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>trialweapon</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
weapon players spawn with in trial, defaults to melee only (0)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..10

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>varslock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines if vars are locked; 0 = off, 1 = helper, 2 = supporter, 3 = moderator, 4 = operator, 5 = administrator, 6 = developer, 7 = creator, 8 = nobody

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>vetolock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines who may force match votes; 0 = helper, 1 = supporter, 2 = moderator, 3 = operator, 4 = administrator, 5 = developer, 6 = creator, 7 = nobody

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voteinterm</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0 = must wait entire time, 1 = passes if votethreshold is met, 2 = passes if unanimous

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>votelimit</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
time in milliseconds intermission voting lasts

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
45000

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>votelock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines at which privilege level votes are locked, accordigng to votelocktype; 0 = off, 1-6 = supporter/helper/moderator/operator/admin/creator can select recently played maps, 7-13 = support/helper/moderator/operator/admin/creator only can vote, 14 = no voting

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..7

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>votelocktype</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines the vote locking type; 0 = off, 1 = lock level only, 2 = lock level can select prevmaps

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>votestyle</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
determines how mid-match votes are handled; 0 = votes don't pass mid-match, 1 = passes if votethreshold is met, 2 = passes if unanimous

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>votethreshold</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
auto-pass votes when this many agree

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.5

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>votewait</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time in milliseconds before a player may cast another vote (to avoid flooding)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
2500

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT IDF\_ADMIN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>wavepushscale</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
scale of the hitpush force used in a wavepush

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>wavestunscale</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0.0..1000000.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>weaponinterrupts</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
56

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..254

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>weaponswitchdelay</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
500

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>zoomlimitmax</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
65

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..150

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>zoomlimitmin</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
10

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1..150

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>zoomlock</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0 = unrestricted, 1 = must be on floor, 2 = also must not be moving, 3 = also must be on flat floor, 4 = must also be crouched

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0..4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>zoomlocktime</b> <i>&lt;milliseconds&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
time before zoomlock kicks in when in the air

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
500

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>zoomtime</b> <i>&lt;value&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines how long it takes for the rifle scope to zoom in and out, the rifle uses the primary fire mode unless the scope is fully zoomed in

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
variable

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
100

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1..2147483646

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_REWRITE IDF\_COMPLETE IDF\_CLIENT

</td>
</tr>
</table>

