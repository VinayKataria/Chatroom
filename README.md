## About 
This is a simple multi-client chat server using `sockets` written in `python`. 

The server asks for username when user wants to join the chatroom and accepts the connection only if the username is unique. It then broadcasts the message from one client to all other clients connected. Also informs about the entry/exit of any client.

## Download
Run the following command in your terminal to save the repository in your system
> $ git clone hhttps://github.com/VinayKataria/Chatroom.git

## Run
Once you are in the directory where `server.py` or `client.py` file exists, run by typing the following commands in your terminal.

### Server
> $ python server.py

### Client
> $ python client.py hostname

#### Example
For server and client running on the same system
![server_censored](https://user-images.githubusercontent.com/46609498/118347024-a7660880-b55d-11eb-9345-cb786b35f257.jpg)
![client_censored](https://user-images.githubusercontent.com/46609498/118347027-a7fe9f00-b55d-11eb-8c34-24585da85081.jpg)
