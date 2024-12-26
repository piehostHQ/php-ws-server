# PHP WebSocket Server with Ratchet

This project demonstrates a simple WebSocket server using PHP and the Ratchet library. It allows real-time communication between the server and a basic HTML/JavaScript client.

## Features

- Establishes a WebSocket connection on port `8080`.
- Sends and receives messages in real time.
- Displays received messages dynamically on a simple HTML client.

## Prerequisites

- PHP 7.4 or higher
- Composer (PHP dependency manager)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/php-websocket-server.git
   cd php-websocket-server
Install dependencies using Composer:

```bash
composer install
```
Run the WebSocket server:
```bash
php server.php
```
Open the index.html file in a browser:
The file includes the client-side code for sending and receiving messages through the WebSocket.
How It Works
Server Code (server.php):

Sets up a WebSocket server using Ratchet.
Listens for connections on ws://localhost:8080.
Client Code (index.html):

Connects to the WebSocket server using WebSocket API.
Allows the user to send messages through an input field.
Displays received messages dynamically in a chat window.
Example Interaction
Start the server using:

```bash
hp server.php
```
Open index.html in your browser.

Enter a message in the input field and click "Send."

The server will broadcast the message back to the client, and it will appear in the chat window