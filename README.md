COMPANY NAME:CODTECH IT SOLUTIONS 
NAME : R Porkodi 
Intern ID : CT04DG2796
DOMAIN : JAVA PROGRAMMING 
Duration : 4 weeks 
MENTOR : Neela Santosh 

Java Multithreaded Chat Application

A simple console-based client-server chat application built in Java using Sockets and Multithreading. This application allows multiple clients to connect to a single server and chat in real-time.

Features

Single combined file for server and client (ChatApp.java)

Server supports multiple clients using Thread and ConcurrentHashMap

Clients can send and receive messages simultaneously

Exit any client with exit command

 Easy to run: choose Server or Client at runtime

 Technologies Used

Java Sockets (java.net.Socket)

Multithreading (Runnable, Thread)

Concurrent Collections (ConcurrentHashMap)

Console I/O (BufferedReader, PrintWriter)

 How to Run

1. Compile

javac ChatApp.java

2. Run Server

java ChatApp
# Choose option 1 to start the server

3. Run Client(s)

Open another terminal and run:

java ChatApp
# Choose option 2 to start a client

You can start multiple clients in separate terminals.

💬 Chat Commands

Type messages to send to all clients

Type exit to leave the chat


output : 


