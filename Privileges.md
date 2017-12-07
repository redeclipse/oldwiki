Players can [apply](http://www.redeclipse.net/apply) for an account that allows them to authenticate as registered users. Registration is optional, so users are free to play anonymously. Some accounts have special privileges (privs) that serve for game moderation or server administration. These are indicated in-game as icons, which are shown to the left of all player names.

### Privs icons

The below table gives an overview of all the icons and their meaning.

| local                                                                                                       | global                                                                                       | authentication | lvl |                                    role                                    |
|-------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|----------------|-----|:--------------------------------------------------------------------------:|
|                                                                                                             | <img src="bot.png" title="bot.png" alt="bot.png" width="40" />                               | bot            | 0   |                           A.I. controlled player                           |
|                                                                                                             | <img src="nobody.png" title="nobody.png" alt="nobody.png" width="40" />                      | none           | 0   |                        players that did not identify                       |
|                                                                                                             | <img src="player.png" title="player.png" alt="player.png" width="40" />                      | player         | 1   |                        players with regular accounts                       |
| <img src="localsupporter.png" title="localsupporter.png" alt="localsupporter.png" width="40" />             | <img src="supporter.png" title="supporter.png" alt="supporter.png" width="40" />             | supporter      | 2   |                       can change most game variables                       |
| <img src="localmoderator.png" title="localmoderator.png" alt="localmoderator.png" width="40" />             | <img src="moderator.png" title="moderator.png" alt="moderator.png" width="40" />             | moderator      | 3   | [can mute, kick, manage teams](Admin_Guide#Moderation_Commands "wikilink") |
| <img src="localoperator.png" title="localoperator.png" alt="localoperator.png" width="40" />                | <img src="operator.png" title="operator.png" alt="operator.png" width="40" />                | operator       | 4   | [higher moderation, e.g. bans](Admin_Guide#Moderation_Commands "wikilink") |
| <img src="localadministrator.png" title="localadministrator.png" alt="localadministrator.png" width="40" /> | <img src="administrator.png" title="administrator.png" alt="administrator.png" width="40" /> | administrator  | 5   |                       full control of server settings                      |
|                                                                                                             | <img src="developer.png" title="developer.png" alt="developer.png" width="40" />             | developer      | 6   |                       core developers of the project                       |
|                                                                                                             | <img src="founder.png" title="founder.png" alt="founder.png" width="40" />                   | founder        | 7   |        [founders](Contributors#Team_Lead "wikilink") of the project        |

Of course, [bots](Bot "wikilink") are not related to player accounts, but they have their own icons to readily distinguish them from human ("real") players. Some privilege levels can be either local or global. Local privs are given to registered players on specific servers, as described in a following section. In contrast, global privs are valid on all public servers.

### Levels and lock variables

The levels shown [above](#Privs_icons "wikilink") (column **lvl**) refer to the usage of certain server variables that define the minimum privs required to perform a specific action. This allows server owners to give more liberal rights to lower player levels. The same levels can also be used to restrict map editing, joining a game or even connecting to the server. To learn more about these variables, search for *lock* in the *variables* menu, which is accessible from the game's main menu.

### Local privs

If you host a game server, you are free to specify local privs for selected players. To add existing user accounts (including your own) to your local server user lists, in [servinit.cfg](Server_Setup#Configuration_Files "wikilink") add:

    addlocalop <handle> <s|m|o|a>

Where "s" is supporter, "m" is moderator, "o" is operator, and "a" is administrator.

If you do not have an account, it is still possible to claim local administrator rights using a password specified in [servinit.cfg](Server_Setup#Configuration_Files "wikilink"):

    adminpass <password> 

This password can be entered via the *setpriv* command, which also servers to claim helper status.

    /setpriv <password>

### How to apply for an account

Open registrations are available for all recurring players. If you play Red Eclipse with any regularity and would like others to be able to identify you, please visit:

<http://www.redeclipse.net/apply>.

Once you have received an authkey and added it to your [config.cfg](Game_Settings#config.cfg "wikilink"), you are free to identify when connecting to a game server. For this you find a checkbox in two of the in-game menus, the server menu (F2) and the user profile menu.
