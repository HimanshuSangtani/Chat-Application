# Real Time Chat Application

This application built using Angular-9 Node.js, MongoDB ,Express, Socket.io, Mongoose, RESTful Web Service.

# Features

  <li>Uses Angular-9 for Frontend Management </li>
  <li>Uses Express as the application Framework.</li> 
  <li>Real-time communication between a client and a server using Socket.io.</li>
  <li>Uses MongoDB, Mongoose  for storing messages and querying data.</li>
  <li>Uses RESTful Web Service for serve different platforms</li> 
   
# Installation

### Running Locally

Make sure you have Node.js and npm install.

1. Clone or Download the repository
<pre>git clone https://github.com/HimanshuSangtani/Chat-Application.git
cd Chat-Application</pre>
2. Install Dependencies
<pre>npm install</pre>
3. MongoDB start for need <pre>mongod</pre>command from a different terminal.

4. Start the Application
      <pre>node/nodemon server.js</pre>
   Application runs from localhost:3000.

## How It Works

A database called "private-chat" named is created via code.
The nickname, msg, group information is also kept in the table named Messages.

User to user messaging:

   <pre> /w username messagetext</pre> the message is sent as.

## Sockets

Having an active connection opened between the client and the server so client can send and receive data. This allows real-time communication using TCP sockets. This is made possible by Socket.io.

The client starts by connecting to the server through a socket(maybe also assigned to a specific namespace). Once connections is successful, client and server can emit and listen to events.

## RESTful

Using HTTP requests, we can use the respective action to trigger every of these four CRUD operations.  
 <li>POST is used to send data to a server — Create</li>
<li>GET is used to fetch data from a server — Read</li>
<li>PUT is used to send and update data — Update</li>
<li>DELETE is used to delete data — Delete </li>

## SCREENSHOTS

This is How it Looks like.


![s2](https://user-images.githubusercontent.com/55733010/93244085-cb8f0100-f7a6-11ea-8b05-493751da6701.png)
![s2](https://user-images.githubusercontent.com/55733010/93244218-02fdad80-f7a7-11ea-8e84-f982fa9e24e5.png)
![s2](https://user-images.githubusercontent.com/55733010/93244303-24f73000-f7a7-11ea-8302-a32d31d2d21b.png)
![s2](https://user-images.githubusercontent.com/55733010/93244362-3dffe100-f7a7-11ea-874a-39eae7307162.png)
