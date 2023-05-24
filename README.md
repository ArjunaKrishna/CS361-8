# CS 361 - Instructions

Download and Install Pycharm and a python version. 

pip install python 

1. Start the Server: Open PyCharm and create a new Python project. Create a new file called "Server.py" in the project. Copy the code for the server implementation into the "Server.py" file. Run the "Server.py" file. This will start the server and make it ready to receive requests. 

2. Start the Client: Open a new terminal or command prompt. Navigate to the directory where you have the Python project. Create a new file called "Client.py" in the same directory. Copy the code for the client implementation into the "Client.py" file. Run the "Client.py" file. This will start the client and allow you to send requests to the server. 

Sending and Receiving Requests: With the server and client running in separate terminals, you can now send requests for IEM data. The available choices for IEMs are: MoondropBlessing2, 7HzTimeless, EtymoticER2SE/ER2XR, and MoondropAria. In the client terminal, enter one of the available IEM types as a string without any spaces. The client will send the request to the server. The server will receive the request and process it. The server will generate a response containing the full path to an image representing the requested IEM. The server will send the response back to the client. The client will receive the response from the server. The client will display the full path received from the server to the user. If the user enters an IEM type that is not one of the available choices, the client will display the message "That's not one of the available choices!".

UML Sequence Diagram: 

![image](https://github.com/ArjunaKrishna/CS361-8/assets/102319952/bb7e82e1-e4a5-41df-91ea-bd42566cf966)

