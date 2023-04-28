# Chat application using sockets in Java

The program in question is a chat server and client application that enables clients to connect to the server and communicate with one another by sending chat messages. The server is capable of accepting incoming connections from clients and broadcasting received chat messages to all other connected clients. The program utilizes three distinct command protocols, namely LOGIN name, CHAT message, and QUIT.

To use the program, it is necessary to first execute the ChatServer program, which will start the server socket and enable it to listen for incoming client connections. Following this, the Chat client program can be launched, and multiple instances of the client program can be run concurrently to establish multiple client connections to the server.
