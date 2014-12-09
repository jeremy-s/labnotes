#Lab Notes 12-8

##

###Final Exam

Friday 9AM. Never try to make tricky. Always a wink or two.

Also, all materials for class due on 13th. Turn in through courseworks.

###Network tools

To ping the server, you send 64 bytes to the server and measure the latency (how long it takes you to get a response back).

	ping google.com

Another command:

	traceroute google.com

Shows you what you run into on every hub, etc. And now you can use foreign websites to see stuff. On each hop, the packet knows where it's going next. Trying to find a route for the network.

Real-time data on internet filters is applicable by using this stuff. You can try to predict censorship, thereby determining internal policy.

###SSH

ssh is a session-based protocol. Not sending packets in a random way. What we're going to do is build a tunnel.

If you can create a secure tunnel to an aws server, you can ssh into that server, establish a secure connection, and then get whatever info you want.

Change keys to where they're only visible to you

	chmod gw-rwx <keyname>