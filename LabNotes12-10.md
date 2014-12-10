#Epigraph: Cloud

###How to Do It (Ubuntu)

ssh -i ~/first-server.pem ubuntu@address (xx.xxx.x.xxx) 

###Things to Learn

**Further instructions on DH notes**

rsync = syncs a folder

scp = securely copies files

cron = daemon to execute scheduled commands

You can cron an rsync command to do backups! Or combine it with scp so that you can copy files at regular intervals.

###AWS Has Other Hard Drives

S3 is a service. Doesn't really need a server. Like a dropbox.

EBS: Elastic Block Storage. You can grow them. Check out Dennis's tutorial for elastic block mounting.

Glacier: Not live, but very stable.

Snapshots: ways to capture all the data simultaneously. You can share snapshots, etc. Instead of copying stuff you can just give someone access to it so they can mount it to their own server. Many government websites do this now. Like giving you a hard drive.

You can also image the whole server. Just take a snapshot, make it available. Yay.

You can automate all this in order to orchestrate. All of this is scriptable. You can elastically automate scalability.