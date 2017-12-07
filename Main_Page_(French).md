**Cette page a été mise à jour pour Red Eclipse 1.4.**

Red Eclipse est un jeu de tir subjectif futuriste, rapide et addictif. Il est multiplateforme et entièrement libre. Il est pour l’instant seulement disponible en anglais.

## Aperçu

Le développement commence en juin 2010 comme fork de Blood Frontier, un mod de Sauerbrauten, et la première version stable est sortie en mars 2011. Le jeu, codé en C++, utilise le moteur Cube 2 et la SDL.

Le jeu hérite de la licence de Cube 2, la Zlib, et les médias sont sous CC-BY-SA. Le nom et le logo sont quand à eux couverts par une [licence spécifique (en)](https://sourceforge.net/apps/trac/redeclipse/browser/trademark.txt).

Red Eclipse possède un éditeur de carte en ligne intégré, très pratique pour tester ensuite la carte. Il possède également un client [IRC](IRC "wikilink") intégré pour parler aux membres de la communauté (anglaise) en allant dans *Help* → *Live Support*.

## Installation

Des binaires sont disponibles pour Windows et Mac OS (32 bits), et Linux/BSD (32/64 bits) et peut fonctionner sur un matériel peu puissant.

Attention! N’installez pas la versions SVN sinon vous ne pourrez peut-être pas vous connecter aux serveurs, car le protocole peut changer entre deux versions.

### Windows et Mac OS X

L'installation est très simple, il suffit de télécharger l’exécutable, le lancer et vous laisser guider.

### GNU/Linux - BSD

#### Via les dépôts

-   Ubuntu
    -   Ubuntu 12.04 et 12.10: vous devez ajouter ce [PPA](https://launchpad.net/~arand/+archive/redeclipse). En ligne de commande:
        -   `sudo` `add-apt-repository` `ppa:arand/redeclipse` `&&` `sudo` `apt-get` `install` `redeclipse`
    -   Ubuntu 13.04: contient la dernière version disponible dans les dépôts multiverse.
    -   PlayDeb [PlayDeb](http://www.playdeb.net/software/Red%20Eclipse) (seulement dans le *Ubuntu 12.04* dépôt).
-   Debian
    -   Vous pouvez ajouter les dépôts [experimental](http://wiki.debian.org/fr/DebianExperimental) (n’oubliez pas d’inclure les dépôts (non-officiels) «contrib» et «non-free»).
    -   Vous pouvez aussi télécharger manuellement les paquets [redeclipse](http://packages.debian.org/experimental/redeclipse), [redeclipse-server](http://packages.debian.org/experimental/redeclipse-server) et [redeclipse-data](http://packages.debian.org/experimental/redeclipse-data) (vous devez choisir l’architecture pour télécharger).
-   Archlinux : il existe un PKGBUILD disponible sur AUR.
-   Chakra : disponible dans le dépôt *games*.

Le jeu est aussi disponible dans d’autres distributions mais sous d’anciennes versions (ou le jeu met longtemps à être mis à jour), il est donc conseillé d’employer la deuxième méthode ci-dessous pour ces distributions.

#### Via l’archive

-   Installez les paquets *sdl*, *sdl\_mixer* et *sdl\_image*.
-   Téléchargez [l’archive «linux\_bsd»](https://sourceforge.net/projects/redeclipse/files/latest/download?source=files).
-   Décompressez l’archive (clic droit sur le fichier → option du style «décompresser») ou en ligne de commande :

`tar -xf redeclipse_1.3_nix_bsd.tar.bz2`

-   Lancez le script *redeclipse.sh* (cliquez sur le fichier) ou en ligne de commande :

`cd redeclipse/`
`./redeclipse.sh`

-   Si cela ne marche il manque peut-être les droits d’exécution, cela peut se régler dans les propriétés du fichier ou en ligne de commande:

` chmod u+x redeclipse.sh`

## Configuration

### Traduction française

Voici en exclusivité la traduction de Red Eclipse faite par [Sinma](Utilisateur:Sinma "wikilink"). Elle n’est pas complète mais traduit une bonne partie des menus ainsi que les astuces.

Vous trouverez toutes les instructions [sur le forum](http://forum.freegamedev.net/viewtopic.php?f=72&t=3701).

### Utilisation avec le Bépo

Si vous utilisez la disposition de clavier Bépo, vous pouvez aller voir sur [le wiki du Bépo](http://bepo.fr/wiki/Utilisateur:Sinma/Red_Eclipse).

## Gameplay

Il est basé sur des armes équilibrées, des mouvements agiles et des modes de jeu très variés. Les mouvements, le rythme de jeu et le level design sont inspirés d*'Unreal Tournament* tandis que les brûlures, le saignement et le comportement de certaines armes ont été repris de *Team Fortress 2*.

Mais le jeu apporte de nouvelles choses, comme un système d’impulsion qui apporte un joueur une nouvelle façon de se déplacer dans un niveau à condition d’avoir assez d’énergie, son système de munitions (nombre de munitions indiquées autour du réticule, chargeurs illimités), supprimant le besoin de connaître à fond un niveau et de plus se concentrer sur le combat et la coordination des mouvements, ce qui abaisse le temps d’apprentissage mais sans perdre la profondeur de jeu. D’autres concepts comme le réticule-radar ont déjà fait leurs preuves et rendent le jeu plus intuitif.

Les armes sont équilibrées, et on regagne de la vie petit à petit. Il n’y a donc pas d’objets (à part les armes). Mais on peut changer beaucoup de variables des armes (modèle et couleur, nom, dommages, personnalisation des projectiles, physique) et de l’environnement (gravité, mouvement des joueurs, puissance des impulsions), notamment utilisé sur certain serveurs ce qui change complètement la manière de jouer.

Il y a dans plusieurs cartes des téléporteurs et des propulseurs («sauteurs») qui rendent le jeu plus dynamique. Les tirs et projectiles sont affectés par ces éléments (passent dans les téléporteurs, sont envoyés dans les air par les propulseurs et déviés par les courants d’air des propulseurs à air).

### Déplacements

Le mouvement est un élément fondamental dans Red Eclipse: vous devez bouger pour survivre. Les pas d’esquive et propulsion permettent un déplacement rapide et d’esquiver facilement les attaques. Vous pouvez marcher/rebondir sur un mur 3 fois avant de tomber. Avancer tout droit est dangereux, car il est facile de vous viser: ne pas bouger est donc risqué. Mais moins vous bougez, plus vous êtes précis et plus vite vous rechargez votre barre d’impulsion.

Déplacements classés par rapidité/précision/régénération : Marcher baissé → Marcher → Courir → Tomber/sauter/nager → Propulsions/pas d’esquive/Glissade.

### Modes de jeu

|                                       |                                                                                                                                                                                                                                                                                                                                                                                                              |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Editing (éditeur)                     | Un éditeur de cartes hors-ligne ou en ligne en coopération.                                                                                                                                                                                                                                                                                                                                                  |
| Deathmatch (match à mort)             | Match à mort classique.                                                                                                                                                                                                                                                                                                                                                                                      |
| capture-the-flag (capture de drapeau) | Capture de drapeau classique.                                                                                                                                                                                                                                                                                                                                                                                |
| defend-the-flag (défense de drapeaux) | Défense de drapeau classique.                                                                                                                                                                                                                                                                                                                                                                                |
| bomber-ball (balle-bombe)             | Prenez la balle et mettez-la dans les buts adverses. Regardez la minuterie de la bombe, ça va exploser si vous la gardez trop longtemps. Faites des passes à vos coéquipiers pour l’emmener là-bas. Si l’autre équipe la détient, tuez le transporteur ou interceptez-la au vol.                                                                                                                             |
| time-trial (contre-la-montre)         | Parcourir une carte spéciale jusqu’au bout, mourir fait revenir au point de départ. Parfait pour s’entrainer et maitriser les différents déplacements du jeu.                                                                                                                                                                                                                                                |
| gauntlet (défi)                       | Il faut faire un maximum de tours (atteindre un endroit précis de la carte) ou défendre cette endroit. Lorsque quelqu’un fait un tour, il marque un point pour sont équipe, disparait et réapparait quelques secondes plus tard au point d’apparition de l’équipe. Les équipes changent de rôle à la moitié du temps de jeu. Nos meilleurs temps sont affichés, comme en time-trial, mais à titre indicatif. |
||

### Mutateurs

Les mutateur (mutators) sont des sortes d’options en compléments des modes, et proposent de complètement modifier un élément du gameplay. Certains mutateurs ne sont pas compatibles entre eux ou exclusifs à certains modes de jeu.

|                      |                                                                                                                                               |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| multi                | 4 équipes s’affrontent.                                                                                                                       |
| ffa (free for all)   | Chacun pour soi.                                                                                                                              |
| Coop (coopération)   | Humains contre ordinateurs (nombre d’humains/nombre de bots = 2/3 par défaut).                                                                |
| instagib             | 1 de vie (donc mort en un coup), rifles uniquement.                                                                                           |
| medieval             | Les joueurs apparaissent avec des épées et ne peuvent avoir d’autres armes.                                                                   |
| kaboom               | Les joueurs apparaissent avec 2 grenades et 2 mines uniquement, rechargeables un par un.                                                      |
| duel                 | Un combat un 1 contre 1, le perdant devient spectateur. Les joueurs spectateurs jouent chacun leurs tour contre le joueur resté dans l’arène. |
| survivor (survivant) | Comme duel, mais avec tous les joueurs apparaissent en même temps (dernier homme debout).                                                     |
| classic              | Vous ne choisissez pas vos armes et apparaissez avec le pistolet uniquement. Des armes que vous pouvez prendre apparaissent par terre.        |
| onslaught (assaut)   | Apparition de robots (*grunts*) et de tourelles (*turrets*) sur la carte.                                                                     |
| jetpack              | Vous pouvez vous envolez, mais attention à la jauge d’impulsion!                                                                              |
| vampire              | Faire des dégâts vous redonne de la vie.                                                                                                      |
| expert               | Vous ne pouvez faire de dégâts qu’avec des tirs dans la tête.                                                                                 |
| resize               | Vous devenez plus petit quand vous prenez des dégâts, et grandissez quand vous faites des dégâts aux autres joueurs.                          |
||

#### Capture the flag

|                    |                                                                                       |
|--------------------|---------------------------------------------------------------------------------------|
| Quick (retour)     | Un drapeau lâché retourne instantanément à la base.                                   |
| Defend (défendre)  | Un drapeau lâché doit être défendu avant qu’il ne disparaisse pour revenir à la base. |
| Protect (Protéger) | Il faut garder le drapeau ennemi pour gagner des points.                              |
||

#### Defend the flag

|                |                                                       |
|----------------|-------------------------------------------------------|
| Quick (rapide) | Les drapeaux sont sécurisés plus vite que la normale. |
| King (roi)     | Un seul drapeau au centre de la carte.                |
||

#### Bomber ball

|                |                                                               |
|----------------|---------------------------------------------------------------|
| Hold (détenir) | Garder la balle un maximum de temps pour marquer des points.  |
| Touchdown      | Il faut rentrer dans les buts adverses avec la balle sur soi. |
||

#### Gauntlet

|                     |                                                                |
|---------------------|----------------------------------------------------------------|
| Timed (chronométré) | Les équipes se battent pour faire le meilleur temps.           |
| Hard (difficile)    | Les joueurs de l’équipe adverse ont un bonus de vie permanent. |
||

### Combats

On peut jouer à Red Eclipse avec des vrais joueurs et/ou des bots aussi bien en local qu’en ligne (jusqu’à 16 joueurs). On peut personnaliser son perso (pseudo, sexe, couleur, accessoires).

Il y a plus de [55 cartes officielles (informations obsolètes)](http://sourceforge.net/apps/mediawiki/redeclipse/index.php?title=Official_Maps) et le jeu supporte le téléchargement automatique des cartes non-officielles.

#### Armes

##### À distance

| Arme                    | Description                                                                                                                                                                                                                                                                                           | Munitions                                                                                                                                                                                                | Attaque                                                            | Attaque alternative                                                                                                                                                                                                                                                                                   |
|-------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Pistol (pistolet)       | Arme par défaut plutôt faible, semi-automatique, utile pour finir les ennemis. N’apparait pas par terre.                                                                                                                                                                                              | 10 balles                                                                                                                                                                                                | Tirs rapides, un tir à la fois,                                    | Utilise deux munitions donc plus puissant mais moins rapide.                                                                                                                                                                                                                                          |
| Sword (épée)            | Arme faisant saigner qui peut attaquer en continu si vous maintenez le clic. Bondir sur l’ennemi vous garantit un coup critique. Unique arme en mode *Medieval*.                                                                                                                                      | Non                                                                                                                                                                                                      | Coup horizontal rapide.                                            | Coup vertical plus lent faisant de gros dommages.                                                                                                                                                                                                                                                     |
| Shotgun (fusil à pompe) | Semi-automatique, recharge automatiquement 2 balles par 2 balles.                                                                                                                                                                                                                                     | 8 cartouches                                                                                                                                                                                             | Tire une balle rapide                                              | Tir puissant utilisant deux cartouches qui se fragmente, rebondissent par terre et font saigner                                                                                                                                                                                                       |
| SMG (fusil automatique) | Arme automatique.                                                                                                                                                                                                                                                                                     | 40 balles                                                                                                                                                                                                | Tirs très rapides peu précis                                       | Tir utilisant 2 balles, plus puissant mais moins rapides                                                                                                                                                                                                                                              |
| Flamer (lance-flamme)   | Brule.                                                                                                                                                                                                                                                                                                | 25 unités de carburant                                                                                                                                                                                   | Automatique, tire à moyenne distance un rayon concentré de flammes | Semi-automatique, tir une grosse boule de feu qui roule dans les virages et rebondit, maintenir pour une plus grosse boule                                                                                                                                                                            |
| Plasma                  | Tire des boules de plasma.                                                                                                                                                                                                                                                                            | 20 charges                                                                                                                                                                                               | Automatique, tirs rapides à moyenne portée avec dégâts de zone     | Semi-automatique. Tir une «Grande boule bleue», attirant les ennemis à proximité. Chargez plus longtemps pour une boule plus grosse mais plus lente                                                                                                                                                   |
| Rifle (sniper)          | Unique arme en mode *Instagib*.                                                                                                                                                                                                                                                                       | 5 rayons                                                                                                                                                                                                 | Faisceau à très longue portée                                      | Lunette de visée, faites tourner la molette de la souris pour ajuster le niveau de zoom                                                                                                                                                                                                               |
| Grenade                 | Cliquez pour lancer, maintenez pour charger. Plus vous maintenez, plus elle explosera tôt après le lancé. Votre vitesse affecte sa trajectoire — foncez vers l’avant pour la lancer plus loin, sautez ou tombez pour différents effets. Provoque des brulures. Appuyez sur *k* pour le mode kamikaze! | Vous pouvez tenir deux grenades à la fois                                                                                                                                                                | Grenade «classique»                                                | Grenade collante                                                                                                                                                                                                                                                                                      |
| Mine                    | Une mine que l’ont peut coller sur n’importe quelle surface (y compris les joueurs, ce qui peux être drôle…)                                                                                                                                                                                          | Lance la mine en mode explosion (si un autre joueur passe à proximité, la mine explose et l’électrise ce qui lui fait perdre de la vie en continu pendant quelques temps et le ralenti considérablement) | Vous pouvez tenir deux mines à la fois                             | Lance la mine en mode barrière (si un autre joueur passe dans le fin rayon de lumière que la mine produit perpendiculairement à sa base, le rayon grossi et fait des dégâts tout en attirant la cible comme le ferait une grosse boule bleue (cf. tir secondaire du Plasma), puis la mine se détruit) |
| Rocket (lance-roquette) | Provoque des dégâts de zone et des brulures. Apparait à un endroit proche du centre de la carte.                                                                                                                                                                                                      | 1 roquette non rechargeable                                                                                                                                                                              | Tir droit                                                          | Tir guidé (bougez la souris pour le diriger)                                                                                                                                                                                                                                                          |
||

##### Corps à corps

| Arme         | Description                                                                                             | Effet                                                                                                                                                                                                                   |
|--------------|---------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Melee        | Vous pouvez tenir n’importe quelle arme et le faire dans n’importe quel mode. Très utile en *Instagib*. | Après un mouvement propulsé, appuyez sur [Special](#Touches "wikilink") en étant au sol pour donner un coup de poing, ou en étant dans les airs pour donner un coup de pied qui vous fera sauter plus haut s’il réussi. |
| Fist (poing) | Uniquement en *time-trial*.                                                                             | Un coup de poing rapide.                                                                                                                                                                                                |

#### Points

Red Eclipse utilise un système de points pour déterminer le vainqueur d’une partie. Les points de tous les joueurs sont additionnés pour donner le score de l’équipe.

##### Tous les modes

| Action                                                          | Points |
|-----------------------------------------------------------------|--------|
| Tuer quelqu’un                                                  | 3      |
| Suicide (avec une arme)                                         | -3     |
| Suicide (tomber dans le vide ou exploser avec la touche K)      | -1     |
| Aider à tuer quelqu’un (message «…helped by \[votre\_pseudo\]») | 1      |

##### Capture-the-flag

| Action                                  | Points |
|-----------------------------------------|--------|
| Tuer quelqu’un qui tient votre drapeau  | 6      |
| prendre le drapeau adverse              | 3      |
| Apporter le drapeau ennemi à votre base | 5      |
| Rapporter le drapeau à votre base       | 5      |

##### Defend-the-flag

Sécuriser un drapeau: 1 point.

#### Succès

Si vous remplissez certaines conditions, un message s’affichera à l’écran (ex : faire un tir dans la tête). Certains donnent des points supplémentaires au joueur.

| Succès                      | Description                                                                                          | Points |
|-----------------------------|------------------------------------------------------------------------------------------------------|--------|
| FirstBlood (Premier sang)   | Faites votre première victime de la partie.                                                          | 1      |
| HeadShot (Tir dans la tête) | Fonctionne avec toutes les armes (dont coups de poings/pieds sauf le Flamer et Plasma rechargé)      | 1      |
| Critical (coup critique)    | Ne donne pas de points *a priori*.                                                                   | 0      |
| Revenge (revanche)          | Tuer un joueurs qui vous a tué plusieurs fois à la suite                                             | 1      |
| x2                          | Tuer 2 joueurs à la suite dans un certain laps de temps, mourir ne fait pas perdre la série de morts | 0      |
| x3                          | Comme x2 mais tuer 3 joueurs                                                                         | 0      |
| Multi Kill                  | Comme x3 mais tuer plus de 3 joueurs                                                                 | 1      |
| Dominating                  | Lorsque que l’on tue quelqu’un 5 fois à la suite sans qu’il nous tue.                                | 1      |
| Carnage                     | Tuer 5 joueurs sans mourir                                                                           | 1      |
| Slaughter (tuerie)          | Tuer 10 joueurs sans mourir                                                                          | 1      |
| Massacre                    | Tuer 15 joueurs sans mourir                                                                          | 1      |
| Bloodbath (bain de sang)    | Tuer 20 joueurs sans mourir                                                                          | 1      |

## Touches

|                                  |                                                                                                                                                                                                                                                |                                   |
|----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------|
| **Action**                       | **Description**                                                                                                                                                                                                                                | **Touche(s) par défaut**          |
| **Dans le jeu**                  |
| forward (avancer)                | Appuyer deux fois pour faire un pas d’esquive vers l’avant/l’arrière/sur la gauche/sur la droite, propulse si dans les airs                                                                                                                    | UP (↑) W                          |
| backward (reculer)               | DOWN (↓) S                                                                                                                                                                                                                                     |
| left (gauche)                    | LEFT A (←)                                                                                                                                                                                                                                     |
| right (droite)                   | RIGHT D (→)                                                                                                                                                                                                                                    |
| scroll up                        | Défilement haut: arme suivante, augmente le niveau de zoom du *Rifle*.                                                                                                                                                                         | LEFTBRACKET (\[) MOUSE4 (Clic 4)  |
| scroll down                      | Défilement bas: Arme précédente, diminue le niveau de zoom du *Rifle*.                                                                                                                                                                         | RIGHTBRACKET (\[) MOUSE5 (Clic 5) |
| enter spectator                  | Entrer dans le mode spectateur                                                                                                                                                                                                                 | HOME (DÉBUT)                      |
| exit spectator                   | Sortir du mode spectateur                                                                                                                                                                                                                      | END (FIN)                         |
| attack (attaque)                 | Attaque «normale»                                                                                                                                                                                                                              | MOUSE1 (Clic Gauche)              |
| alt-attack (attaque alternative) | Attaque secondaire                                                                                                                                                                                                                             | MOUSE2 (Clic droit)               |
| reload                           | Recharger                                                                                                                                                                                                                                      | R MOUSE3 (Clic milieu)            |
| use                              | Ramasser une arme                                                                                                                                                                                                                              | E                                 |
| jump                             | Sauter, 2 fois (sans appuyer sur une touche de direction) pour un double saut                                                                                                                                                                  | SPACE (ESPACE)                    |
| run/walk                         | Maintenez pour marcher                                                                                                                                                                                                                         | LCTRL (CTRL droite)               |
| crouch                           | S’accroupir, glisser (en maintenant après un saut et avant de toucher le sol ou après un pas d’esquive)                                                                                                                                        | LSHIFT (MAJ droite) C             |
| parkour/kick                     | Marcher sur les murs (sauter à côté d’un mur mais parallèle, maintenir cette touche et avancer), rebondir sur les murs (Sauter puis appuyer sur cette touche en face d’un mur), utiliser les [ coups de poing/pied](#Corps_à_corps "wikilink") | Q                                 |
| drop                             | Lâcher son arme                                                                                                                                                                                                                                | Z                                 |
| flag/bomb                        | Lâcher le drapeau/la balle                                                                                                                                                                                                                     | F                                 |
| cmd input                        | Afficher l’invite de commande                                                                                                                                                                                                                  | F11                               |
| all chat                         | Parler à tout le monde                                                                                                                                                                                                                         | RETURN (ENTRÉE) T                 |
| team chat                        | Parler à son équipe uniquement                                                                                                                                                                                                                 | Y                                 |
| toggle console                   | Afficher la console                                                                                                                                                                                                                            | F11                               |
| toggle editing                   | Afficher le menu du mode édition                                                                                                                                                                                                               | F1                                |
| screenshot                       | Prendre une capture d’écran                                                                                                                                                                                                                    | pas de touche par défaut          |
| add bot                          | Ajouter un joueur ordinateur                                                                                                                                                                                                                   | INSER                             |
| delete bot                       | Supprimer un joueur ordinateur                                                                                                                                                                                                                 | DELETE (SUPPR)                    |
| maps menu                        | Menu de choix des cartes                                                                                                                                                                                                                       | F2                                |
| maps voting                      | Menu de vote des cartes                                                                                                                                                                                                                        | F3                                |
| claim privileges                 | Demander des droits au serveur                                                                                                                                                                                                                 | pas de touche par défaut          |
| loadout menu                     | Menu de choix des armes                                                                                                                                                                                                                        | F6                                |
| team menu                        | Menu de choix d’équipe                                                                                                                                                                                                                         | F7                                |
| voice compass                    | Menu pour les voix qui s’adressent à tout le monde                                                                                                                                                                                             | V                                 |
| team compass                     | Menu pour les voix qui s’adressent uniquement à l’équipe                                                                                                                                                                                       | X                                 |
||

### Armes

Attention, ici les touches chiffrés désignent les touches de la rangée supérieure du clavier en qwerty (et pas ceux du pavé numérique) et ne fonctionneront pas en azerty. Il faudra donc (si vous souhaitez les utiliser) les changer, sachant que certaines touches comme ^) ne sont pas acceptées par le jeu (mais les touches accentuées fonctionnent).

| Nom de l’arme        | Melee | Pistol   | Sword | Shotgun       | SMG               | Flamer       | Plasma | Rifle  | Grenade | Rocket         |
|----------------------|-------|----------|-------|---------------|-------------------|--------------|--------|--------|---------|----------------|
| Description          | Mélée | Pistolet | Épée  | Fusil à pompe | Fusil automatique | Lance-flamme | Plasma | Sniper | Grenade | Lance-roquette |
| Touche(s) par défaut | 0     | 1        | 2     | 3             | 4                 | 5            | 6      | 7      | 8 G     | 9              |
||


