# chat-server-NodeJs
Created a chat server using socket in NodeJs. It is just a learning project to understand how read and write to sockets in NodeJs.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

* [node](https://nodejs.org/en/download/) - The runtime environment to run server Javascript file.
* NetCat - Networking utility which reads and writes data across network connections using the TCP/IP protocol.
  * [Windows](https://joncraton.org/blog/46/netcat-for-windows/)
  * [Unix](https://www.tecmint.com/netcat-nc-command-examples/#:~:text=Netcat%20(or%20nc%20in%20short,%2C%20or%20UNIX%2Ddomain%20sockets.)

## Running the script

Make sure you installed all the prerequisites.

### Getting Server Started

Open your terminal or powershell window to run server file

```
node chat.js
```
It will start chat server at localhost:8000 port, you will see **Server Bound** message on terminal/powershell.

### Getting Client connected to server port(8000)

Open another terminal or powershell window to connect with server.
NC(NetCat) utility is used to connect client to server with different network protocols.
```
nc localhost 8000
```

## Authors

* **Vitthal Anjana**



