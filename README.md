# Echo-Client-Server

# Echo Client/Server Program

This project contains a simple echo client/server program that demonstrates the use of the `socket` module in Python. The client sends a message to the server, and the server sends the message back to the client.

## Prerequisites

To run this project, you will need to have Python installed on your computer.

## Running the Server

To start the server, use the following command:

python echoserver.py


The server will listen for incoming connections on a specified port (the default is 8000).

## Running the Client

To start the client, use the following command:

python echoclient.py


The client will prompt you to enter a message to send to the server. The server will receive the message and send it back to the client, which will then print the received message.

## Customizing the Server and Client

You can customize the behavior of the server and client by modifying the `handle_client` function in the server script and the `send_message` function in the client script. For example, you could add additional functionality to the message handling process, such as logging the messages or implementing additional commands.

## Additional Notes

The `socket` module is a powerful tool for building networked applications in Python. This simple echo client/server program is just a demonstration of the capabilities of the `socket` module, and there are many other ways that it can be used in a variety of applications.
