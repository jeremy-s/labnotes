#Lab Notes 11-12

##Models of Version Control

A: Multiple copies, multiple copies. Improvement: pretend you can't make copies.  
B: Only one version (cloud model).  

General Problems: multiple versions, asynchronicity, etc.

We're learning get, but we're really learning versioning period.

Ideas behind git: imagine you're writing and you're keeping a journal. Journal is a ledger of what you've done; on top of files, you'll also keep a journal of changes.

Git operates with a notion of project. Project is just a folder.

Imagine one layer on your hard drive. Every time you do something and save, you basically lose the history of changes.

To solve this problem, add another layer: journal or git if you prefer.

But you need another layer between journal and fs called stage. Imagine stage as a desk on which you combine groups of changes. From stage, you commit to journal.

This is very good for visibility of labor, btw.

**ALL THIS STUFF IS LOCAL**

ls -a: find hidden files. If you preface a directory with a dot, it will be hidden.

##Configuring a Project

git init: tells git to keep track of that folder.

git add: package certain changes.

git commit: commit changes to the journal.

##Remote Server

There is a remote server which contains a copy of your journal.

git push: synchronize your journal with the remote server.

This remote host is called **github**. Or you could run your own git host.

##Multiple Authorship

Another person can sync from the remote server and push to it as well.

git pull: take everything and pull it down.

##Other Commands

git status: find the status of branches, commits, and what you can commit

git commit -m: Add a message of the commits

To take directory out of version control: rm -rf .git/

git checkout file.ext: roll back your local copy based on most recent pushed to server.

##Caveat Programmer

If you put your home directory under version control, everything will be copied. Be careful. Don't transmit private data.

##Comparing Versions & Plaintext

Github compares versions line by line via plaintext. If you do a binary-encoded file, it will still try to compare them. But it becomes a little meaningless.