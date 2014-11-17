##10-15 Lab Notes

###find

find . -name "ora*"

find [where] [what type] [search string]

This dot thing is just one option. It actually accepts regexes. The query can be super-complex.

An example.

###grep

grep "orange" oranges.txt

or

grep "orange" *

-search all files! But stop at directories (i.e. not recursive by default.)

grep -r "orange" *

-recursive search

###Word Counting!

grep "whale" pg2701.txt | wc

Pipes output into a command called wordcount.

lines on which that word appears-total words of those lines-characters

###sort

sort oranges.txt

Can you speed up repeated searches by sorting!?! Maybe...

Note that this sorting happens in output, not in file.

If you want a real wordcount, you have to tokenize.

###uniq

uniq instances. -c gives counts

###sed

sed 's/day/night/' 24hrs.txt

substitute night for all days. Does not change in file.

-i flag allows you to do it in place (changing file)

Proper way to do -i

sed 's/day/night/' 24hrs.txt >> night.txt

###Assignment

not graded, but finish it.

1. Analyze the treatment of gender in Moby Dick. Look for words that have to do with male/female, etc.
	1. First, grab the text of MD.
	2. Then make two lists of gendered words, with each word on a new line. (he, male, him, etc.)
	3. grep the context of female words and context of all male words, creating 2 new files.
	4. Now get rid of common English words in each of those files.
	5. Then sort and count words in each file.
2. Weasel words. Take a piece of writing you wrote and check for weasel words.
	1. Copy three pieces of writing you wrote for someone else. Save as plaintext.
	2. Make a list of words that are weasel words (words you hate in writing, i.e. "clearly," etc.)
	3. Write a script that replaces those words with blanks.

Some of these commands can take a file as an attribute (grep), i.e. you can load in a file of patterns to search for.