# COE768-Project
Computer Networks Course Project - P2P Network

This program creates a Peer-to-Peer network using C sockets.

The Server program is to be used on a machine which will act as an index server for the network. Clients will connect to the index server
and register content that they would like to host to the rest of the network. All other clients connected to the network can see what
content is available on the network and send a request to the index server. The index server will then respond to the client with the 
IP address of the client hosting that piece of content. The 2 clients will then setup a TCP connection and communicate with each other 
to organize the file transfer.
