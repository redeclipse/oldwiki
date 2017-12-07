Cross compiling is the process of compiling code to run on a different platform than the platform running the compiler. For example, building a Windows runnable while running Linux is cross compiling. More on [cross compilers](http://en.wikipedia.org/wiki/Cross_compiler) on Wikipedia.

## For Windows from GNU/Linux

-   Install mingw-w64 or equivalent, on a Debian-like system, this can be done via

`sudo apt-get install mingw-w64`

-   Compile for x86 and amd64 using the commands. Of course you need to [obtain the source code](Obtain_development_version#Download_via_SVN "wikilink") before this step.

`make -C src PLATFORM=crossmingw32 clean install`
`make -C src PLATFORM=crossmingw64 clean install`

-   Note: If on Ubuntu 12.04, the package g++-mingw-w64 may also be required.

## For GNU/Linux from Windows

-   Don't. Just don't.

