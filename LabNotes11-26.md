#Lab Notes 11-26

###Final Project

Do a tutorial that's fun for you. Contribute it to the Minimally Viable Digital Citizen. Concept that you like and have some notes on. One page. Always start with why you should care.

Topics:  
Markdown  
Plaintext  
File System  
Terminal Navigation (i.e. find/sed)  
Networking (ping/traceroute)  
Crypto (pgp/bitcoin)  
Pandoc  
biblio (zotero/bibtec/Latex/typesetting)  
Package Management (apt/brew)  
git (version control)  
file permissions

###Pull Request

Branching: you have a primary remote. Every person who's not the editor makes a clone (called a branch). You have full permissions in the branch b/c it's on your side. When you finish your changes, you'll file a pull request. This is basically saying, "Hey, fix this stuff."

This allows chunking of tasks. Each task is modular, and there's an ease of integration. Every software company has some kind of version control.

Branches are difficult. Documents are difficult. Code is difficult.

If you're a big company, you host your own server on the cloud which runs your own version of git.

###File Permissions Tutorial

Pendulum btwn centralized, decentralized computing. Supercomputers vs. pc's. With the internet, we're becoming more centralized (cloud computing). Companies like microsoft, for example: microsoft really doesn't want you to install software on your own computer. Log in, write stuff, log out.

First thing a machine asks you to do is to create a new account. All machines have some level of user control.

	ls -l

In Windows, every user has a name and a group. Think of this as a physical permissioning problem. By default, your username is also your groupname.

directory  
read  
write  
xecute

user/group/world

Ex: drwxr-xr-x:
User (u) can read, write, execute
Group (g) can read, execute.
Other (o) can read, execute.

####Modifying Permissions

chmod (change file mode bits)

	chmod g+w test.txt

Give group write permissions for test.txt

If you use that when permissions are already given, it will take it away.

sudo group: you can do everything if you're a member of that group.  
Super Users Do Group.

	sudo touch test.txt

Allows you to exercise administrative permissions.