#Lab Notes 12-3

##Servers & Cloud Computing

###Intro

5 to 10 years ago, a person who herds servers was a sysadmin. 2nd class citizen. Were like a janitor. Today, though, we've seen a move to creating servers as if they're software. Today, servers are an abstraction.

Cloud orchestration: you can write a piece of code that spins out a thousand servers, etc.

Today, devops. A mixture between operations and development.

###Required Work

Courseworks: under assignments, you should see 4 assignments which are formal requirements of this course.

-Submit weasel words.

-Send Lab Notebook link in the repository.

-MVC Tutorial comes from a lab notebook. Clean it up and submit a tutorial into the common repository. Instructions on courseworks.

-Everything should be due 13th of December.

###Servers

You write a file, listen to music, etc. every day.

In the olden days, we relied on servers and used terminals to access a centralized server. Servers run the world. Serve us movies, songs, etc.

A lot of people will use old desktops repurposed as servers.

###Creating a Virtual Server in the Cloud

Platform-as-a-service. Cloud we're using: AWS.

Three or four others:  
 - Microsoft's Azure  
 - Google's thing

What you need for a server:  
 - some processing power  
 - operating system (to listen for requests)  
 - memory/storage, which is an abstraction (s3 or elasticblock/EBS or Glacier)
 - database
 - identity service (for payments and such)
(i.e. a computer)

Scalable.

Ports in/out. Numbered.

We don't have control of the material substratum. Current problem: should the Public Library of America be put on AWS, or should they invest in their own servers?

Early-on, the cloud was internal to Amazon. But they made it modular.

Also, governance is digital. Logging into some centralized server.

Most companies today have their stuff hosted in the cloud.

Leaving behind servers as a service.

###Amazon AWS

####EC2

Make sure the components you launch are in the same region.