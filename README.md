# Chat Application using C and Sockets

This repo contains a simple chat application built using C programming langugae, utilizing TCP/IP sockets for communication between multiple clients and a server. Clients can connect to the server, send messages, and receive messages from other connected clients via the server.

## Commands

#### Running the Server

1. Compile the server program:
   ```bash
   ./server <port_number>
   ```

Replace <port_number> with your desired port number.

2. Run the server:
   ```bash
   ./server <port_number>
   ```

### Running the Client

1. Compile the Client program:
   ```bash
   ./client <server_ip> <server_port>

   ```
2. Run multiple Clients
   ```bash
   ./client 127.0.0.1 12345
   ```

Replace 127.0.0.1 with the server's IP address and 12345 with the server's port number.

## Working

#### The server and clients communicate via TCP/IP sockets.

#### Clients can connect to the server and exchange messages with each other through the server.
