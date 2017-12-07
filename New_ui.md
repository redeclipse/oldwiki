For the next release, Red Eclipse 1.6, the entire menu system is being replaced with a new ui system. This means that already in the current development version, all gui commands and all derived menus have been dropped, and new versions of these menus are work in progress.

## New ui usage

There is currently no documentation available. Help for expanding the instructions in *config/usage.cfg* is welcome.

## List of new ui commands

Below is a list of commands extracted from *src/engine/ui.cpp*.

| command           | args       | arguments                                                                                                                                     |
|-------------------|------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| uigroup           | e          | uint \*children                                                                                                                               |
| uirootname        |            |                                                                                                                                               |
| newui             | ssssi      | char \*name, char \*contents, char \*onshow, char \*onhide, int \*windowflags                                                                 |
| uiallowinput      | b          | int \*val                                                                                                                                     |
| uiexclusive       | b          | int \*val                                                                                                                                     |
| uiwindowflags     | b          | int \*val                                                                                                                                     |
| uioverridepos     |            |                                                                                                                                               |
| uisetpos          | ff         | float \*xpos, float \*ypos                                                                                                                    |
| uiresetpos        |            |                                                                                                                                               |
| uicursorx         |            |                                                                                                                                               |
| uicursory         |            |                                                                                                                                               |
| uicursortype      | b          | int \*val                                                                                                                                     |
| showui            | s          | char \*name                                                                                                                                   |
| hideui            | s          | char \*name                                                                                                                                   |
| hidetopui         |            |                                                                                                                                               |
| topui             |            |                                                                                                                                               |
| hideallui         |            |                                                                                                                                               |
| toggleui          | s          | char \*name                                                                                                                                   |
| holdui            | sD         | char \*name, int \*down                                                                                                                       |
| pressui           | sD         | char \*name, int \*down                                                                                                                       |
| uivisible         | s          | char \*name                                                                                                                                   |
| uiname            |            |                                                                                                                                               |
| uihlist           | fe         | float \*space, uint \*children                                                                                                                |
| uivlist           | fe         | float \*space, uint \*children                                                                                                                |
| uilist            | fe         | float \*space, uint \*children                                                                                                                |
| uigrid            | iffe       | int \*columns, float \*spacew, float \*spaceh, uint \*children                                                                                |
| uitableheader     | ee         | uint \*columndata, uint \*children                                                                                                            |
| uitablerow        | ee         | uint \*columndata, uint \*children                                                                                                            |
| uitable           | ffe        | float \*spacew, float \*spaceh, uint \*children                                                                                               |
| uispace           | ffe        | float \*spacew, float \*spaceh, uint \*children                                                                                               |
| uioffset          | ffe        | float \*offsetx, float \*offsety, uint \*children                                                                                             |
| uifill            | ffe        | float \*minw, float \*minh, uint \*children                                                                                                   |
| uitarget          | ffe        | float \*minw, float \*minh, uint \*children                                                                                                   |
| uicolour          | iffe       | int \*c, float \*minw, float \*minh, uint \*children                                                                                          |
| uimodcolour       | iffe       | int \*c, float \*minw, float \*minh, uint \*children                                                                                          |
| uivgradient       | iiffe      | int \*c, int \*c2, float \*minw, float \*minh, uint \*children                                                                                |
| uimodvgradient    | iiffe      | int \*c, int \*c2, float \*minw, float \*minh, uint \*children                                                                                |
| uihgradient       | iiffe      | int \*c, int \*c2, float \*minw, float \*minh, uint \*children                                                                                |
| uimodhgradient    | iiffe      | int \*c, int \*c2, float \*minw, float \*minh, uint \*children                                                                                |
| uiline            | iffe       | int \*c, float \*minw, float \*minh, uint \*children                                                                                          |
| uioutline         | iffe       | int \*c, float \*minw, float \*minh, uint \*children                                                                                          |
| uiimage           | siiffe     | char \*texname, int \*c, int \*a, float \*minw, float \*minh, uint \*children                                                                 |
| uiimagevgradient  | siiiffe    | char \*texname, int \*c, int \*c2, int \*a, float \*minw, float \*minh, uint \*children                                                       |
| uiimagehgradient  | siiiffe    | char \*texname, int \*c, int \*c2, int \*a, float \*minw, float \*minh, uint \*children                                                       |
| uicroppedimage    | siifftttte | char \*texname, int \*c, int \*a, float \*minw, float \*minh, tagval \*cropx, tagval \*cropy, tagval \*cropw, tagval \*croph, uint \*children |
| uistretchedimage  | siiffe     | char \*texname, int \*c, int \*a, float \*minw, float \*minh, uint \*children                                                                 |
| uiborderedimage   | siitfffe   | char \*texname, int \*c, int \*a, tagval \*texborder, float \*screenborder, float \*minw, float \*minh, uint \*children                       |
| uitiledimage      | siiffffe   | char \*texname, int \*c, int \*a, float \*tilew, float \*tileh, float \*minw, float \*minh, uint \*children                                   |
| uitriangle        | iffie      | int \*c, float \*minw, float \*minh, int \*angle, uint \*children                                                                             |
| uitriangleoutline | iffie      | int \*c, float \*minw, float \*minh, int \*angle, uint \*children                                                                             |
| uimodtriangle     | iffie      | int \*c, float \*minw, float \*minh, int \*angle, uint \*children                                                                             |
| uicircle          | ife        | int \*c, float \*size, uint \*children                                                                                                        |
| uicircleoutline   | ife        | int \*c, float \*size, uint \*children                                                                                                        |
| uimodcircle       | ife        | int \*c, float \*size, uint \*children                                                                                                        |
| uitextfill        | ffe        | float \*minw, float \*minh, uint \*children                                                                                                   |
| uitext            | tfe        | tagval \*text, float \*scale, uint \*children                                                                                                 |
| uifont            | se         | char \*name, uint \*children                                                                                                                  |
| uiclip            | ffgge      | float \*sizew, float \*sizeh, float \*offsetx, float \*offsety, uint \*children                                                               |
| uiscroll          | ffe        | float \*sizew, float \*sizeh, uint \*children                                                                                                 |
| uiscrollbutton    | e          | uint \*children                                                                                                                               |
| uiscrollarrow     | fe         | float \*dir, uint \*children                                                                                                                  |
| uihscrollbar      | e          | uint \*children                                                                                                                               |
| uivscrollbar      | e          | uint \*children                                                                                                                               |
| uisliderbutton    | e          | uint \*children                                                                                                                               |
| uisliderarrow     | fe         | float \*dir, uint \*children                                                                                                                  |
| uihslider         | rfffee     | ident \*var, float \*vmin, float \*vmax, float \*vstep, uint \*onchange, uint \*children                                                      |
| uivslider         | rfffee     | ident \*var, float \*vmin, float \*vmax, float \*vstep, uint \*onchange, uint \*children                                                      |
| uitexteditor      | siifsie    | char \*name, int \*length, int \*height, float \*scale, char \*initval, int \*mode, uint \*children                                           |
| uifield           | riefie     | ident \*var, int \*length, uint \*onchange, float \*scale, int \*immediate, uint \*children                                                   |
| uikeyfield        | riefe      | ident \*var, int \*length, uint \*onchange, float \*scale, uint \*children                                                                    |
| uimodelpreview    | ssffffe    | char \*model, char \*animspec, float \*scale, float \*blend, float \*minw, float \*minh, uint \*children                                      |
| uiplayerpreview   | iiiisffffe | int \*model, int \*colour, int \*team, int \*weapon, char \*vanity, float \*scale, float \*blend, float \*minw, float \*minh, uint \*children |
| uiprefabpreview   | sifffe     | char \*prefab, int \*colour, float \*blend, float \*minw, float \*minh, uint \*children                                                       |
| uislotview        | iffe       | int \*index, float \*minw, float \*minh, uint \*children                                                                                      |
| uivslotview       | iffe       | int \*index, float \*minw, float \*minh, uint \*children                                                                                      |
| uiminimap         | siffffe    | char \*texname, int \*c, float \*dist, float \*border, float \*minw, float \*minh, uint \*children                                            |
| uiminimapcolour   | siiffffe   | char \*texname, int \*c, int \*c2, float \*dist, float \*border, float \*minw, float \*minh, uint \*children                                  |
| uiradar           | fffffe     | float \*dist, float \*offset, float \*border, float \*minw, float \*minh, uint \*children                                                     |
| uiradarblip       | sifffffe   | char \*texname, int \*c, float \*yaw, float \*blipyaw, float \*dist, float \*minw, float \*minh, uint \*children                              |
| uialign           | ii         | int \*xalign, int \*yalign                                                                                                                    |
| uiclamp           | iiii       | int \*left, int \*right, int \*top, int \*bottom                                                                                              |
| uiposition        | ff         | float \*x, float \*y                                                                                                                          |


