# Reading Class 13

Socket.io Chat Example

1) The client/user interact with a server. The user establishes a connection to the server so that data can be sent bi-directionally. When the client sends a message to the server, the server sends a message to every client that's connected to it.

2) The proof of life is the console.log that a user/client has connected.

3) Broadcast is the flag that sends the message to everyone except the itself (the socket that sent the event);

Rooms

1) A room is a sub-space that a socket can join and be grouped under. If the server emits to the room, sockets in the room can hear it, while sockets not subscribed to the room cannot.

2) .join into a room with the room ID.

3) .leave the room with the room ID.

Namespace

1) A namespace is a mechanism to group sockets and related events.

2) Event handlers, Rooms and middleware

3) A possible usecase for namespaces is setting up a applications that contain a place for chat, a place for notifications and a place for real-time updates.