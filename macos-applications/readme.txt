Mac OS applications can simply be executable shell scripts in the /Applications folder.
However, they must be contained in a Folder with an identical name and the .app file ending.

E.g., create a folder "Foo.app" inside /Applications and move your script, called "Foo",
into this folder.
Make sure the script is executable (with chmod +x Foo) and that it has a minimum size (several
bytes, pad with zeros if white spaces if necessary).
Also make sure the script has a shebang at the top, e.g. #!/bin/bash for bash scripts.
