# ConMan
ConMan: Connection Manager

The purpose of this project is to create a program that makes it easier to connect to servers / remote machines. 

For example with my current setup it's possible for me to remote into a terminal server, which connects to another terminal server, which may connect to another terminal server, and then possibly a cluster and then to the actual machine I want, which is a total of 5 hops and a minimum of 5 logins.

The idea is to be able to store the server names / ip address' as well as the path ConMan has to take to get there. For example to get to Machine8 ConMan has to go through TS03>FS105>Machine8
