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

<img width="543" alt="Screenshot 2023-08-31 at 9 17 43 PM" src="https://github.com/abhirambussa/SE20UARI036_Client-Server/assets/121299178/b28d1546-ac77-4eb9-baa9-3c0eed25e368">

## Dependencies

The following dependencies are required to run the program:

* Flask
* requests
* json
