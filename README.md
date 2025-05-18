# networking
Authenticated Remote Command Server


This Python script implements a basic remote command execution server with simple password-based authentication using SHA-256 hashing. Once authenticated, the server allows sending shell commands to the connected client and displays the responses in real-time.

**Features**:
Listens on port 9999 for incoming connections[if yo want to change the port also, most of the cases port 9999 is free to access]
SHA-256 based password authentication (secret123 as default)
Interactive command prompt to send commands to the client
Graceful shutdown using quit command
**Note**:the port number same in both client and server
