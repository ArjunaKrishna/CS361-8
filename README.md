# CS 361 - Instructions

Download and Install Pycharm and a python version. 

pip install python 

This is a very simple server and client program. For sending data, the server file must be ran first and then the client file. After that, the user can enter an IEM they like and get the full path of the image. 

Client.py: This file will take the data from the user and send it to the server. After getting the response from the server, this file will display the full path to the user. 

Server.py: This file will process the data received from the client and send a response containing the file path to the client. 

For optimal usage, the user should run Client.py on one terminal and Server.py on the other. 

Data that can be sent should be strings without any spaces. They can be either of these four: MoondropBlessing2, 7HzTimeless, EtymoticER2SE/ER2XR, MoondropAria. 

Data will be received as a link to an images showing that particular IEM. If the user sent something random other than these four IEM types, he/she will get this message "That's not one of the available choices!". 

UML Sequence Diagram: 

![image](https://user-images.githubusercontent.com/102319952/236111138-67163f1e-d585-4a55-a1e0-b39ee02f36c3.png)
