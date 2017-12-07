Waypoints are a set of points that the bot AI uses to navigate around the map. Without waypoints, bots are prone to running into map hazards, such as into lava or off midair platforms. The waypoint file ({mapname}.wpt) is one of the files automatically sent along with the map in multiplayer situations.

<table cellspacing="10" style="width:100%">
<tr>
<td width="174">
**/dropwaypoints 0|1**

</td>
<td width="219">
0: no waypoints are dropped, *default* 1: waypoints are dropped while not in editing mode

</td>
</tr>
<tr>
<td width="174">
**/showwaypoints 0|1**

</td>
<td width="219">
toggles the visibility of the path that connects waypoints. Waypoints are always visible if they are being dropped.

</td>
</tr>
<tr>
<td width="174">
**/savewaypoints \[s\]**

</td>
<td width="219">
saves a .wpt file containing the current maps waypoints. The default waypoint file is saved as the current map's name. **/savewaypoints custom-name** will save a waypoint file as a custom name.

</td>
</tr>
<tr>
<td width="174">
**/loadwaypoints \[s\]**

</td>
<td width="219">
loads a .wpt file containing waypoints. A waypoint file matching the maps name is loaded by default. **/loadwaypoints custom-name** will load another waypoint file with a custom name.

</td>
</tr>
<tr>
<td width="174">
**/delselwaypoints**

</td>
<td width="219">
Select the area in which the waypoints you want to remove are. Then use this command to delete the waypoints in the selected area. Note that waypoints spawn *above* terrain, not *in* terrain, so you may want to move your selection upwards.

</td>
</tr>

