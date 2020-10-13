# Python_MiniProject
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/37b3ea6e5be84bc9835e599b71e8c419)](https://www.codacy.com?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=99002478/Python_MiniProject&amp;utm_campaign=Badge_Grade)
![CI](https://github.com/99002659/Python_MiniProject/workflows/CI/badge.svg)


TCP Client-Server Threads
The goal of this project is to build a tcp client and a tcp server
Requirements

    Python > 3.5.x.
    The server should listen on port 3443
    The server should accept a maximum of 100 connected clients
    The server should send the current date to each client every 10 seconds
    The client should be a command line application and should connect to the server with a TLS connection
    Once started the client should receive the current date from the server every 10 seconds
    The client should listen on the standard input and send a text message to the server every time the return key is pressed, the server should respond to the client with the same string but reversed
    All the implementation must be covered with automated tests and cloned using Visual Studio



Execute

Use the following command to execute the code.

1 - Open the terminal and run the Server Program first: python threadServer.py
2 - Open new terminal tab then start the Client program: python threadClient.py
in order to connect n clients, repeat step 2 n times
Automated tests

In order to run the automated tests run the script: python tests.py


