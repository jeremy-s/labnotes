9/10

UNIX = built around plaintext.

Commands

pwd = path of current location
/ = root address
cd - = goes to last directory
pushd [name] = pushes onto stack of locations you've been to recently. Apparently it won't let you keep
	pushing duplicates
popd = pops off stack of locations you've been to recently, taking you to the one popped
~ = shortcut for home
cat = concatenate and display in stdout

ls by itself takes an implicit argument of the current path. But if you did something like
“ls ..” you'd get the subdirectories of the directory above your current location. So the full command is
“ls [path]

UNIX command structure: [verb] [-adverb] [object]