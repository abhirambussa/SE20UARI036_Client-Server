# Client-Server   Assignment
### SE20UARI036

## Client-Server Message Exchange
This repository contains a simple Python program that allows you to send and receive messages between a client and server system.

## Server Code
The server code is implemented using the Flask framework. It exposes an API endpoint at /api/messages that can be used to send and receive messages.

## Client Code
The client code uses the requests library to send a message to the server.

## How to Use
To use the program, first start the server by running the following command in the server directory:

`python server.py`

Then, in a separate terminal window, start the client by running the following command in the client directory:

`python client.py`

<img width="499" alt="Screenshot 2023-08-31 at 9 12 41 PM" src="https://github.com/abhirambussa/SE20UARI036_Client-Server/assets/121299178/5a5784d2-affc-4490-960f-77b47c51c937">


The client will send a message to the server. The server will print the message to the console.

## Example

The following is an example of a message that can be sent to the server:

{"message": "Hello from the client!"}

The server will print the following message to the console:

Received message: Hello from the client!

 ![Screenshot 2023-08-31 192830](https://github.com/revanthjavvaji/SE20UARI071/assets/114976742/0acff6c0-7024-4b2f-a65a-b60e67e6c391)

## Dependencies

The following dependencies are required to run the program:

* Flask
* requests
* json
