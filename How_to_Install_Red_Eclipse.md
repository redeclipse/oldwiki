## Windows

-   Download [the Windows installer](http://redeclipse.net/download/windows).
-   When it is done, double click the resulting EXE installer.
-   Run through the prompts to install Red Eclipse on your computer.
-   Run the `Red` `Eclipse` shortcut placed in your Start Menu.

If you get a permission denied error during install, right click the installer and [Run as Administrator](http://windows.microsoft.com/en-us/windows7/how-do-i-run-an-application-once-with-a-full-administrator-access-token). Alternatively, you can change the install location to a user-writable folder (like "\[My\] Documents") during the install process.

## Linux

### Standard Package

-   Install git, curl and the runtime dependencies of Red Eclipse.
    -   On a Debian-like system (e.g. Ubuntu, Linux Mint), this can be done with the command:
        -   `sudo` `apt-get` `install` `git` `curl` `libsdl2-mixer-2.0-0` `libsdl2-image-2.0-0` `libsdl2-2.0-0`
    -   On a Fedora system, this can be done with the command:
        -   `dnf` `install` `curl` `SDL2` `SDL2_mixer` `SDL2_image`
-   Download [the Linux tarball](http://redeclipse.net/download/linux).
-   When it is done, move the resulting TAR.BZ2 file to your home directory (~/ or $HOME = /home/username).
-   Extract the contents into your home directory using your favourite archive utility.
    -   Terminal command: `tar` `-jxvf` `redeclipse_X.Y.Z_nix.tar.bz2`
-   Enter the resulting folder (which will be called `~/redeclipse-X.Y.Z` where X.Y.Z is the version number of the package).
-   Run `./redeclipse.sh`

### AppImage

You can install Red Eclipse as an [AppImage](http://appimage.org) with no dependency installation required. At the moment, only 64-bit AppImages are provided. They should work on any system from 2014 (such as Ubuntu 14.04) onward. After downloading the appimage, make it executable with your file manager or with `chmod` `+x` <path to appimage>. You can then double-click on it or run it from the commandline. Updates will be automatically downloaded and applied.

#### Stable version

Stable appimages will be available soon. Download the latest [stable AppImage](https://redeclipse.net/appimage/stable/redeclipse-stable-x86_64.AppImage), make it executable (using your file manager or running `chmod` `+x` `redeclipse-stable-x86_64.AppImage`). Then, double click the file or run it from the commandline (`./redeclipse-stable-x86_86.AppImage`). That's all you have to do, Red Eclipse should be up and running.

#### Development version

Download the latest [development AppImage](https://redeclipse.net/appimage/master/redeclipse-master-x86_64.AppImage), make it executable (using your file manager or running `chmod` `+x` `redeclipse-master-x86_64.AppImage`). Then, double click the file or run it from the commandline (`./redeclipse-master-x86_86.AppImage`). That's all you have to do, Red Eclipse should be up and running.

#### Server

The standalone server is built as well, you can access all builds at [<https://redeclipse.net/appimage>](https://redeclipse.net/appimage).

#### Advanced options

You can set the following environment variables to configure the AppImage's behaviour:

-   REDECLIPSE\_APPIMAGE\_NO\_UPDATE
    -   If set, will prevent automatic updating.
-   REDECLIPSE\_APPIMAGE\_NOTERM
    -   If set, will prevent the automatic updating from opening a terminal to display progress.
-   REDECLIPSE\_APPIMAGE\_TERM
    -   If set, will use the value of this variable as the terminal program to display update progress.

## macOS

-   Download [the macOS tarball](http://redeclipse.net/download/macos).
-   When it is done, click the resulting TAR.BZ2 file in your downloads folder on the dock.
-   Archive utility will extract the contents into the same folder and open a Finder window with `redeclipse.app` highlighted.
-   Drag and drop the `redeclipse.app` package to your favourite location (Desktop, Applications folder, whatever).
-   Run `redeclipse.app`.

If this is the first time running the app, the operating system complains that it can't run an unsigned package, simply right (or cmd) click and select `Open`. In future you will be able to run the app as normal, this will override the warning for all future attempts. You can also do this [from the command line](http://osxdaily.com/2015/07/15/add-remove-gatekeeper-app-command-line-mac-os-x/).

## Unofficial Builds

**These packages are created by third parties and aren't officially supported by the Red Eclipse project.**

### Debian/Ubuntu repository

There is a Red Eclipse package repository hosted on openSUSE Build Service that you can use to install game and/or server. The packages provided there are newer than distributions' packages, so if you prefer to install Red Eclipse via `apt`, you should install this repository.

Beware that only the latest stable release is available on the repository. It will occasionally receive updates whenenever the `stable` branch on GitHub is updated. If you want to test the latest and greatest version of Red Eclipse, you need to either use an [\#AppImage](#AppImage "wikilink") or install Red Eclipse [from source](#Install_from_source "wikilink").

The oldest supported distributions are Ubuntu 16.04 and Debian 8.0 for the client, and Ubuntu 14.04 and Debian 7.0 for the server.

To install the client, just go to [this site](https://software.opensuse.org/download/package?project=home:TheAssassin:RedEclipse&package=redeclipse) and follow the instructions.

For the server, visit [this site](https://software.opensuse.org/download/package?project=home:TheAssassin:RedEclipse&package=redeclipse-server) instead, and follow the instructions.

The packages are a fork of the original Debian Red Eclipse packages, but have been improved to reduce the size of a server installation.

## If you get stuck

Don't panic! If you have trouble working out how to install and run the game, you can get assistance on our [live chat](http://redeclipse.net/chat) or [forums](http://redeclipse.net/forum). Please be ready to provide as much information as possible, especially what operating system you're on and specifically which package you're trying to install!
