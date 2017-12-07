<table cellspacing="10" style="width:100%">
<tr>
<td width="174">
/skybox

</td>
<td width="219">
loads 6 .jpg or .png images associated by name from the specified directory ex: /skybox skyboxes/gradient will load gradient\_up.png gradient\_dn ect.

</td>
</tr>
<tr>
<td width="174">
/skycolour R G B

</td>
<td width="219">
changes the color of the skybox ex: /skycolour 255 180 180

</td>
</tr>
<tr>
<td width="174">
/yawsky \#

</td>
<td width="219">
sets the placement of the skybox (move the sun's placement)

</td>
</tr>
<tr>
<td width="174">
/spinsky \#

</td>
<td width="219">
controls the speed at which the skybox turns

</td>
</tr>
<tr>
<td width="174">
/cloudlayer

</td>
<td width="219">
loads a specified image to tile as a cloud layer ex:/cloudlayer skyboxes/clouds01

</td>
</tr>
<tr>
<td width="174">
/cloudheight \#

</td>
<td width="219">
-1: bottom of the skybox 1 top of the skybox

<tr>
<td width="174">
/cloudscale \#

</td>
<td width="219">
controls the scale of the cloud layer

</td>
</tr>
<tr>
<td width="174">
/cloudscrollx \#

</td>
<td width="219">
controls the movement speed of the cloud layer on the x axis

</td>
</tr>
<tr>
<td width="174">
/cloudscrolly \#

</td>
<td width="219">
controls the movement speed of the cloud layer on the y axis

</td>
</tr>
<tr>
<td width="174">
/cloudlayercolor R G B

</td>
<td width="219">
controls the color of the cloud layer

</td>
</tr>
<tr>
<td width="174">
/cloudfade \#

</td>
<td width="219">
controls how the cloud layer fades around the edges

</td>
</tr>
</table>
## Importing Skyboxes

1.To create a map with a custom skybox (offline only), you can put them in your [User Content Directory](Map::user_content "wikilink").

2.Navigate to the User Content directory **"Username\\My Documents\\My Games\\Red Eclipse"** and create a new folder named "myskyboxes".

3.Place your six skybox images into this folder. Each of the six image names must end in a corosponding location ex:

imagename\_up.png

newskybox\_dn.png

newskybox\_lf.png

newskybox\_rt.png

newskybox\_bk.png

newskybox\_ft.png

4.Now, run Red Eclipse and open the map you would like to add your custom skybox to. After you've opened the map and are in edit mode, type the following: **/skybox myskyboxes/newskybox**

If you need help creating a skybox, [check out a tutorial on Quadropolis](http://quadropolis.us/node/2339)
