## Mapping Tips

These are general suggestions that will help you create maps for Red Eclipse's gameplay. There is no right or wrong way, and no map is ever perfect. The only rule is to have fun!

![](Mapping scale.jpg "Mapping scale.jpg")

-   While building with cubes it is easy to create structures that are as tall as they are wide. Red Eclipse requires more room to move horizontally.
-   A fun layout is more important than impressive geometric details.
-   Walls are floors! Unless covered with invisible clip material a wall with details will become an obstacle. Players will not be able to run on detailed walls or become stuck in them. Adding details to floors will create a similar problem.
-   Low ceilings and hanging details need to be properly clipped or noclipped so that players do not get stuck or hung on them.
-   Using textures creatively to add detail to your map instead of complex geometry is encouraged when possible.

![](Mapping layout.jpg "Mapping layout.jpg")

-   While building with cubes it is easy to create a map that is a box filled with smaller objects. You are encouraged to experiment and combine cubes to create different shaped hallways and rooms.

![](Mapping figure eight.jpg "Mapping figure eight.jpg")

-   It is more interesting if each room has more than one entrance and a map has no dead-end paths. Sometimes it is helpful to imagine Figure Eight shaped paths when creating a map layout.
-   All weapons and areas should have at least one route that is accessible to bots and players without requiring trick jumps. This allows maps to be played offline with bots.

![](Mapping stairs.jpg "Mapping stairs.jpg")

-   While building with cubes it is easy to create stairs that are too steep. This can cause players to become stuck on them or require players to jump up stairs. Steps that are smaller and have more space between them allow better movement.

![](Mapping lighting.jpg "Mapping lighting.jpg")

-   Light entities can be used as brushes to paint areas with light color instead of many smaller lights at the source object.
-   Lights are usually not white. Sunlight, firelight and natural lights are usually have a red or yellow tint. Man-made lights usually have a green or blue tint.
-   Lights usually have a source such as the sun, a streetlight, a glowing computer screen, or control panel. Some textures have a glowmap assigned to them while some do not.

<!-- -->

-   The size of a mapfile (.mpz) is greatly increased when calculating the lighting. The reason for this is the lightmap texture created with the Calclight command and saved within the mapfile. Increasing the Lightprecision setting greatly reduces the size of the mapfile and adjusting this is recommended if you are sharing a map through a server. A mapfile size of less than 1mb is suggested in this case as it will take many minutes to send or receive a large file over a server.

