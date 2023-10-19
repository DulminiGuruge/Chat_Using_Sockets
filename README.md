# Chat application using sockets in Java

The program is designed to facilitate communication between clients and the server by allowing users to send chat messages. When clients connect to the server, they can exchange messages with one another, and the server will ensure that all connected clients receive the messages sent by other clients. The program relies on three distinct command protocols: LOGIN name, CHAT message, and QUIT.

To use the program, you need to start the ChatServer program first, which initiates the server socket and enables it to listen for incoming client connections. Once the server is up and running, the Chat client program can be launched, and multiple instances of the client program can be run concurrently to establish multiple client connections to the server.
