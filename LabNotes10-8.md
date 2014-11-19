#Notes 10/8

We are now in the danger zone. Untested curriculum here, people.

##Package Management and Uninstalling

Files are files. You don't need to "uninstall" them because no dependencies. But when you install an application, there are many files in many places with many dependencies. And using pieces of OS located elsewhere.

If you take the time, there is a file *somewhere*. Or somewheres...

##Windows' Solution

On a windows machine, Firefox (for example) uses icons shared across many programs. But what about using two programs that use different icon sets? Uninstalling is important for resolving these things.

Microsoft solves this by having dll files. Shared libraries. But a lot of redundancy.

##*nix's Solution

In *nix, they came up with something a little more elegant. All the programs are checked into a repository. A foundation that keeps a secure repository. Each distribution keeps a repository. But the threshold for entry is high.

The repository guarantees that things don't conflict. They run daily tests to make sure this doesn't happen.

Also fixes security problems (trusting look of website).

###A Repository for Mac?

Not an official one. But there is an unofficial one called Brew.

###Other Types of Repositories

Language-based.

 - Ruby (gem).
 - Python (pep).

##Really Powerful Tools

####Search

 - locate
 - find
 - grep
 - awk

####Friends

 - head
 - tail
 - cat

####Flow

 - |
 - >>
 - xargs

####Network

 - wget
 - curl
 - ssh
 - ping
 - traceroute

##Using these Tools

wget [link] = download a file

cat/head: first or last lines.

.pdf is registered with Adobe. The system knows what thing to open what file with based on ext.

If you rename a file to an arbitrary ext, you can do that and it doesn't change the info. But it confuses the OS. But when you try to open it with Adobe, Adobe doesn't care about the extension. It looks at the internal data.

The file is the file. What you call it is arbitrary (although with important implications in context).

##Search!

If you know how to use locate/find/grep/awk, you're "insanely cool."

All of these understand regexes

###locate

Find files as usual.

 -i = ignore case

for some reason must be in quotes...

###find

