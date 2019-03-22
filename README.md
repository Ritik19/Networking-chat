# Networking-chat
A Group chat designed using socket library of Python.

# Description
TCP connection is established for reliable communication. On the server side, the connection is accepted and a new thread is spawned for each client.
The message of each user is broadcasted to all the users and a "user left" is broadcasted when a user leaves chat.  
