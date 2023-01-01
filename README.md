TCP Server and Chat Room

This is a simple TCP server and chat room application implemented in Python. It allows multiple clients to connect to the server and send messages to each other.
Prerequisites

    Python 3.9 or higher
    The socket and threading modules

Running the Server

To start the server, run the following command:

python server.py <host> <port>

Replace <host> with the hostname or IP address of the machine that the server will be running on, and <port> with the port number that the server will listen on.
Connecting to the Server

To connect to the server, run the following command:

python client.py <host> <port>

Replace <host> with the hostname or IP address of the machine that the server is running on, and <port> with the port number that the server is listening on.


Using the Chat Room

Once you have connected to the server, you will be placed in the chat room and can start sending messages to other clients. To send a message, simply type it and press enter. The message will be broadcasted to all other clients in the chat room.


Disconnecting from the Server

To disconnect from the server, type /quit and press enter. This will close the connection and exit the client program.
