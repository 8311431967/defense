__Defense Sample Game
=====================
Game Progamming Algorithms and Techniques  
By: Sanjay Madhav

Information
-----------
This code is a sample tower defense game from my book. While the code
contained herein does have some commenting, for a more comprehensive
analysis of the code, you should read the corresponding chapter from
the book (14).

For any updates to this code, more detailed build instructions,
as well as download links to binaries, visit the page for this project
on the book's website at: http://gamealgorithms.net/source-code/defense/.

Building
--------
There are three different solution files, depending on the platform:

**defense-xna.sln** - This is the XNA 4.0 version which works with Visual
                  Studio 2010 only, and you have to have XNA installed.

**defense-mono.sln** - This is the MonoGame PC version. It will run on either
                   Visual Studio 2010 or 2012, and requires MonoGame
                   (tested with 3.0.1). It may also work in the
                   MonoDevelop IDE.

**defense-mac.sln** - This is for MonoGame on Mac. It requires the free
                  version of Xamarin Studio as well as MonoGame.

Almost all of the C# files are simply shared between the three projects.
The only separate files are the Program*.cs files, which are just really
simple entry point files. Also note that the Bloom post-process effect is
only enabled in the XNA version, as there are some differences in how
MonoGame handles effects.

License
-------
The code is released under the Microsoft Permissilve License, which more
or less means you can use it for whatever you want to, commerical or not.

Though not required, it would be nice if you gave attribution if you end
up using this code in a game of yours. At the very least, I'd love to
hear about any games that end up doing so.

I'm not a lawyer, though, so you'll want to read the full LICENSE file.

