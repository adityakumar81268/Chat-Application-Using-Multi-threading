Chat Application Using Multithreading:

This is a simple multithreaded chat application built using Java Sockets. It supports multiple clients who can chat with each other via a  server.



Features:

1.TCP-based communication  
2.Server handles multiple clients using threads  
3.Broadcasts messages from one client to all others  
4.Console-based interface





Requirements:

1.Java JDK 8 or higher  
2.Terminal or command line interface



Running the application



1. Start the Server
java ChatServer    
The server will start on port 12345.

2. Start One or More Clients
In separate terminals, run:

java ChatClient  
Each client will connect to the server and can send/receive messages.

 Usage:

Type messages in the client terminal and press Enter to send.
Messages will be broadcast to all other connected clients.
Close the terminal to disconnect.  
 File Structure:

 1. ChatServer.Java.      # Server-side code 

2. ChatClient.java   # Client-side code. 

 Notes:

This is a basic example for educational purposes.


 Author:

Developed by:   
Aditya Kumar.      
Janvi Kumari.    
Harsh Raj    
Ria Sahu
