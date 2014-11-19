#Lab Notes 9-24

In our current world, almost every vector has its own specific format.  
One format called plaintext, one editorial environment.  
When you're in control, you control encryption, etc. And you can become much more 
proficient.  
Need to make sure that environment is extensible.  
With opensource editors, you're not buying into a proprietary system if you use markdown.  
Mashable has a list of 78  

-Markdown-
Not identifying stylistic elements; identifying semantic elements.
*Primary Emphasis*
**Secondary Emphasis**
#Heading
##Subheading (etc.)
- list
>quote
[link](address)
` ` code block. ``` for lengthy ones

EMPTY SPACE MATTERS
Forcing return: 2 empty spaces
If you want to make something meaningful, you have to specify it

In linux: nano test.md
It's still a plaintext editor! It will work with this.

Pandoc: not for the weak of heart. Anything into anything.
But it works on a command line.
-can be connected to .bib format and have pandoc look up another entry. Look up DT's tutorial online.

PANDOC
yaml block at the top
---
title: The Title of the Work
bibliography: bib.bib
author: Jeremy
---
You can write a script based on arbitrary tags that places it in the correct folder, etc.
Pandoc is made with academics in mind. It has some extra conventions for academics.

 Pandoc -so tomake.ext target.ext

s: smart option
o: full format, i.e. guess file type based on extension

10/1
##Files
mkdir
touch
cp
mv
rm

##Paths
/ root
~ home
- previous

##Operators
	> >>
| pipes
!

##Search
find grep awk

##network
SCP
SSH
ping
traceroute
rsync
wget

POSIX
v adv n

##GPS
pwd
ls
table world!
Cat
man
-h
--help
history
