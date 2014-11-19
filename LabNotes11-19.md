#Lab Notes 11-19

##More git

###Branching

Imagine you have 3 collaborators. If they push and pull from one remote, this is ok. Easy to reconcile.

But scale up to thousands of contributors. So many things that need arbitration. What's the solution?

Branch. The best way to think about it is to think about syllabi. It lets you parcel changes into uber-groups. You can also try to merge the branches. If both keep expanding, though, it's tough to do.

You can have one branch called testing/development in order to protect the live version. And in order to launch the new one, you merge the branches.

####Other Major Model

Commit stuff into different remotes. Have a main one, make a copy of the remote on the server. Then changes pushed to each remote. Not technically "branches." But when a person on a sub-branch has work to contribute, you do a pull request (i.e. "hey I wrote stuff add it to the master branch"). What you're doing is editing. Person merging pull requests is an editor. Instead of creating new drafts.

Assignment:

Open a new repository on github called lab notes. Go ahead and put your lab notes to the repository. Organize it.