# TCP-Server-using-nodejs
This repository contains a simple TCP server built with Node.js using the built-in net module. The server listens on a specific TCP port, accepts connections from clients, and handles communication.

.The TCP server is created using Node.js and listens for incoming connections on a specified port.


.When a client connects, the server can receive and respond to messages over the TCP connection.

Known Issue
Error: An existing connection was forcibly closed by the remote host.

This error is encountered when clients (like ncat) attempt to connect to the server. The issue is currently unresolved. If you have a solution or a fix, please feel free to edit this README and contribute!
