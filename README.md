# UDP Socket Server Example
This is a simple UDP socket game server example in python. 
Currently the server expects a packet with "connect" in order for a client to connect.
Afterwards, the server will periodically send random colors to all connected clients.
If a client does not send a heartbeat at least once every 5 seconds. The server drops the client.

### Usage
`cd ~`

`mkdir labs` or `cd labs`

`git clone https://github.com/Xian767-6424/udpSocketServer.git`

`cd udpSocketServer`

`python3 udpSocketServer`

* 1. use nano ~/.ssh/authorized_keys to open file in your EC2 server
* 2. copy ssh key and paste into authorized_key file to allow cloud9 to authorize your EC2 sever
