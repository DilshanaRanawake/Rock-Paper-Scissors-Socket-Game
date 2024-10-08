# Client-Server Socket Programming - Rock-Paper-Scissors Game

## Project Overview
This project implements a client-server architecture using C/C++ to facilitate a Rock-Paper-Scissors game between two computers over a network. The server handles multiple clients concurrently, and each client can make a choice (Rock, Paper, or Scissors), with the server determining the winner.

## Features
- **Server-Client Communication**: The server listens for incoming client connections and processes requests from multiple clients simultaneously.
- **Game Logic**: Clients can send their choice (Rock, Paper, or Scissors) to the server, which responds with its own choice and determines the result.
- **TCP Socket Programming**: Communication is implemented using TCP sockets with the Winsock2 library.

## How to Run
### Server Setup
Copy the server.c code into a Windows machine.
Open a command prompt in the directory containing server.c.
Compile the server code with the following command:
```bash
gcc server.c -o server.exe -lws2_32
```
Run the server:
```bash
server.exe
```
### Client Setup
Copy the client.c code into a separate Windows machine.
Open a command prompt in the directory containing client.c.
Compile the client code with the following command:
```bash
gcc client.c -o client.exe -lws2_32
```
Run the client:
```bash
client.exe
```
## Code Files
server.c: Contains the server-side code to accept connections, handle requests, and determine the winner.
client.c: Contains the client-side code to send a request to the server and display the result.

## Prerequisites
GCC compiler (for compiling the C/C++ code).
Winsock2 library (for network communication on Windows).

## Example of Execution
The client sends a choice (Rock, Paper, or Scissors) to the server.
The server generates its own choice and responds with both its choice and the game result.
The client displays the server's choice and the result (Win/Lose/Tie).

## Technologies Used
- C/C++ for programming.
- Winsock2 for socket communication.
- TCP/IP for network communication.

## Contributors
Dilshana Ranawake
Anjula Achinthana
(group project)


