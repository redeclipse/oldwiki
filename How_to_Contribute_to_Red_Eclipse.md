This [guide](http://redeclipse.net/forum/viewtopic.php?f=8&t=598) is a basic introduction to the development model for Red Eclipse, including the procedure for submitting modifications and creating new ideas. It is suggested you read this in its entirety before starting any development related work, as it contains vital information regarding proper etiquette.

### Preliminaries

Red Eclipse development is done with GIT. From there, you are able to create Issues or [Pull requests](Pull_requests "wikilink") (these link to the "base" module, there are separate modules for "data" and "site"). If you are unfamiliar with GIT it is recommended to read a few tutorials on the net in order to avoid asking embarrassing questions. GitHub brings the advantage of a familiar interface with a robust set of features aimed at improving collaborative development and built to handle most of what users need from it, including help documentation.

The tree is split up into the following:

-   base: <https://github.com/red-eclipse/base> - The base environment, including everything needed to build the game.
-   site: <https://github.com/red-eclipse/site> - The entirety of the website, minus runtime config and data.
-   maps: <https://github.com/red-eclipse/maps> - The maps included in the game
-   community: <https://github.com/red-eclipse/community> - Works relevant to Red Eclipse but not included in the game.

There are many other repositories containing assets from specific contributers (e.g. red-eclipse/acerspyro is the repository containing Acerspyro's contributions) and other less central aspects of Red Eclipse, such as the statistics system and the configuration files for the master server (which is the server that serves the server list when looking for servers in the server menu when you select multiplayer).

If you are on Windows and don't like the official GitHub application you can try MSysGit or TortoiseGit. If you are on Linux you should be able to obtain the git command line tools from your distribution/package manager.

Here's a rundown of how to setup a new repository:

`   git clone --recursive `[`https://github.com/red-eclipse/base.git`](https://github.com/red-eclipse/base.git)` redeclipse`

### Content/Idea/Proposal Guidelines

-   Create a piece of content, come up with an idea, or decide to propose a change you want included in Red Eclipse.
-   Then, create a thread for it, either in Maps and Mods for content, or General Discussion for ideas/proposals.
-   Give the community a chance to provide feedback, or answer a poll (minimum time should be about 2 weeks).
-   When you feel you have come up with a finished work, idea, or proposal, submit it to the appropriate git module as an issue or [pull request](pull_request "wikilink").
-   Provide a good description along with a link to your original forum topic.
-   Attach, or provide direct links to, any files you are attempting to have included here.
-   Feel free to share a link to your post while we review it.

### Issue Reporting Guidelines

-   Find an issue in the Red Eclipse game and/or engine, verify that you can reproduce the problem and provide steps on how to do so.
-   Check on the forums or issue tracker to see if your issue has already been reported and/or resolved upstream.
-   When you have verified that the issue still exists and needs to be fixed, submit it to the appropriate git module as an issue or [pull request](pull_request "wikilink").
-   Provide a good description along with a link to your original forum topic (if applicable).
-   Attach, or provide direct links to, any files which demonstrates your issue and any patches you might have here.

### General Guidelines

-   Only submit finalised works (no work-in-progress items please). If you are just looking for general feedback, you can use the forums (or a git fork!).
-   You acknowledge we will probably modify your content before including it (to fix any problems or improve it).
-   If you want to modify it at a later point, changes you make will need to be based on our version, otherwise we may not include your updates.
-   You must provide an explicit, legally enforceable license. Do not use "public domain", or "no commercial use" / "no modification allowed" clauses. If you don't, it will be assumed you are happy to use the Red Eclipse general license which best applies to the work.

If you are unsure about how to license your work, Creative Commons provides a handy selection tool for their licenses at <http://creativecommons.org/choose/> and Red Eclipse content is generally licensed "CC by-sa" (Attribution-ShareAlike), unless otherwise specified: <http://creativecommons.org/licenses/by-sa/3.0/>

#### A Note on Commit Messages

As of yet, there are no strict rules for formatting of commit messages. However, it is good practice to keep commit messages clean and simple while providing a relatively clear idea of what the commit entails. The following is a well-formatted commit message template that is widely used and well regarded. This template is merely a *suggestion*, it need not be strictly adhered to or followed at all.

[Commit Message Template by Tim Pope](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)

Beyond that, [here is a helpful section](http://git-scm.com/book/ch5-2.html#Commit-Guidelines) in the *Pro Git* book that briefly covers creating good commits.

### Forum Utilities

The following BBcodes are available to reference GIT information on the [forum](http://redeclipse.net/forum/):

-   git: references a git commit in a specific module. Example (gives "[base:6400eeaa71021f54ddc9cf730e7b1503dbe69101](http://redeclipse.net/git/base/commit/6400eeaa71021f54ddc9cf730e7b1503dbe69101)"):

`       [git=base]6400eeaa71021f54ddc9cf730e7b1503dbe69101[/git]`

-   issue: references a git issue in a specific module. Example (gives "[base:issue:1](http://redeclipse.net/git/base/issues/1)"):

`       [issue=base]1[/issue]`

-   pull: references a git [pull request](pull_request "wikilink") in a specific module. This is superfluous as PR's are actually issues. Example (gives "[base:pull:2](http://redeclipse.net/git/base/pull/2)"):

`       [pull=base]2[/pull]`
