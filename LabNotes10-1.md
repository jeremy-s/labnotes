##Lab Notes 10/1

OS is a textual system. Literary, in a way.

###Commands
touch: create a blank file

Now put some text inside...

 - echo "x": echoes to the screen by default.

 - echo "x" > test.txt puts it in file
 - > Overwrites by default
 - >> appends

Pipe operator |
 
 - use with less. Less is a paginator.

history | grep "hello"
Search history for any occurrence of hello.

ctrl+r = reverse search through history. Pressing return executes.

*Scary* Commands

 - cp: copy
 - copy current file 'to file' Will overwrite
 - difference btw verb and noun is in space. Spaces in file names choke up. And don't use capitals b/c case sensitivity
 - mv: move. Can be used to rename.
 - rm: remove

-i : ask for confirmation to overwrite. Will not ask for confirmation if no overwrite will happen.

###Notes on Paths

Nouns are always paths. Sometimes they're collapsed.

cp target1.txt ../target1.txt

Longer path = absolute

Shorter = relative

###Deleting a Directory

rm -ri temp2/

-r: recursively running until empty

###wget???

Grab something online

(ctrl+shift+v = paste)

wget link


