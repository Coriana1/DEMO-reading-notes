# Socket.io Chat Example
1. Explain to a non-technical recruiter what the Chat Example (above) does.
  - The Chat Example is a simple web application that allows users to communicate with each other in real-time using a chat interface. It enables multiple users to join the chat room and send messages that are instantly displayed to all connected users. Users can see each other's messages as they are typed and engage in conversations in real-time. It provides a convenient way for people to communicate and interact with each other on a website.
2. What proof of life are we getting on the backend from the above app?
  - the server console logging the message "a user connected" whenever a new user joins the chat room.
3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
  -you can use the 'io.emit()' method with the 'socket.broadcast' flag. The code would look like this: 'socket.broadcast.emit('event', data)'. 

## Rooms
1. What is a room and how might a room be useful?
  -a room is a virtual channel or grouping mechanism that allows you to organize connected sockets into specific groups. A room can be useful when you want to create separate spaces for different topics, user groups, or private conversations.
2. How do you join a room?
  - You can use the 'socket.join()' method on the socket object in Socket.io. 
    The code would look like this: 'socket.join('roomName')'. 
3. how do you leave a room?
  - You can use the 'socket.leave()' method on the socket object. 
    The code would look like this: 'socket.leave('roomName')

## Namespaces
1. What is a Namespace and what does it allow you to do?
  - A way to separate sockets into different channels or namespaces. It allows you to create multiple instances of Socket.io that can run independently and have their own isolated communication channels.
2. Each namespace potentially has its own what? (hint: 3 things)
  - Sockets, Events, Rooms
3. Discuss a possible use case for separate namespaces
  -  In a multi-tenant application where you want to provide isolated communication channels for different clients or user groups.

## Reflection
1. What are your learning goals after reading and reviewing the class README?
- Using name spaces