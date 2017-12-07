A bot is a player controlled by the computer. In online games, the CPU load of bots is distributed over clients.

## Icon

[128px](file:bot.png "wikilink") Bots are easily recognized by the icon right next to their name.

## Orders

Players can give orders to all bots in their team, or to a specific bot.

This can be done with a chat command consisting of two or three keywords.

-   First word: A bot's name, or just **bots** to address all
-   Second word: An order
    -   attack - chase a flag or ball
    -   defend - assist the player or defend a place
    -   forget - go back to the previous order
    -   reset - ignore all previous orders
-   Third word: A target - depends on the order and game mode.

Bots will reply by either confirming the order or with some hints. If an order is incomplete, the bot will reply with available options to complete the order.

## Balancing

By default, when there are not enough players for a specific [map](Game::maps "wikilink"), the places are filled in with bots, and once a new player joins the game, one of the bots gets removed from the game. When playing offline or as a (local) operator, the amount of bots can be controlled via certain variables:

-   botoffset - add or subtract a number of bots per team
-   botbalance - allows to disables bots or specify a limit per team
-   botlimit - the maximum number of bots in total

## Skill and behavior

The skill levels of each bot are randomized in the range set by

-   botskillmin
-   botskillmax

A skill value of 101 means that the bot reacts with full speed and precision. However, that does not necessarily mean that bots are intelligent, especially in team games with complex objectives. Other ways to make bots considerably tougher or weaker in combat are to alter their movement speed (botspeed), maximum health or scale (model size). Changing the model size via *botscale* will scale the absolute movement speed as well.

### skill adjustment

There are also two variables to adjust the skill of each bot based on the bot's deaths and frags count: *botskilldeaths* and *botskillfrags*.

### abilities

It is possible to limit most of the bot's abilities. For this there is a bitfield variable *botabilites*, which can be set as a sum of these flags:

-   move/push = 1
-   jump = 2
-   crouch = 4
-   dash = 8
-   boost = 16
-   parkour = 32
-   melee = 64
-   primary fire = 128
-   secondary fire = 256
-   rigid (unaffected by push/stun) = 512
-   affinity = 1024
-   regen = 2048

### valid targets

The variable *botcollide* and *botteamdamage* define who can be attacked or damaged by the A.I., respectively.

-   players = 1
-   bots = 2
-   enemies = 4
-   ghosts = 8

**Note:** Most of the above variables are also available for drones, grunts and turrets, i.e. neutral units that spawn in [onslaught](Mutator_Tips#onslaught "wikilink") mode.

**Note:** There are separate bot skill and balance variables for some game mutators or modes, in particular [coop](mutator_Tips#coop "wikilink"), where players compete with a larger team of bots.
