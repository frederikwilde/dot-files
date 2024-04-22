Mac OS applications can simply be executable bash scripts in the /Applications folder.
However they must be contained in a Folder with an identical name and the .app file ending.

E.g. create a folder "Foo.app" inside /Applications and move your bash script, called "Foo"
into this folder.
Make sure the script is executable (with chmod +x Foo) and that it has a minimum size (several
bytes, pad with zeros if white spaces if necessary).

