# MultiThreaded-Web-Server
This project demonstrates a basic multithreaded server-client architecture using Java Sockets. The server can handle multiple clients simultaneously using threads, and each client sends a message to the server and receives a response.

SERVER

Listens on port 8010.

Accepts multiple clients concurrently using threads.

Responds to each client with a message.

Handles each client in a separate thread using Consumer<Socket>.


CLIENT

Spawns multiple threads (100 by default).

Each thread opens a socket connection to the server.

Sends a message and prints the server response.



