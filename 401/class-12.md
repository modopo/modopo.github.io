# Reading Class 12

Web Socket

1) A web socket is a bi-directional communication protocol that enables real-time data transfer between a web browser (or other client) and a server over a single, continuous TCP connection.

2) When a client wants to establish a WebSocket connection with a server, it first sends an HTTP request with an "Upgrade" header indicating it wants to switch protocols to WebSocket. The server responds with an HTTP 101 status code, indicating that it agrees to the protocol switch.

3) request

Socket.io

1) io.on() is a method that allows you to listen for various events that occur on the server-side. It is used to handle various events like connection, disconnection, and custom events.

2) Verify that the server logs anything when a client connects or disconnects to the server.

3) The io.emit() method is used to emit an event with a specified name and data payload.

Socket.io vs Web Sockets

1) WebSocket provides a basic mechanism for real-time communication, while Socket.io is a more feature-rich library that abstracts away some of the complexities of working with  WebSockets and provides additional features to make real-time communication more reliable and manageable.

2) You would use Socket.io for real-time updates, compatibility with a wide range of clients.

3) Youl would use Web Socket for low latency, high inputs and bidirectional communications.

OSI Model Explained

1) The OSI (Open Systems Interconnection) model is a conceptual framework used to describe the communication process between computing systems. It consists of seven layers, each of which represents a different aspect of the communication process, starting from the physical layer to the application layer.

TCP Handshakes

1) Imagine you want to send a message to your friend, but you need to make sure they're ready to receive it first. The TCP handshake is like the process of asking your friend if they're ready and waiting for your message. First, you send a message to your friend saying "Are you there?". This is the SYN packet. Your friend receives this message and responds with "Yes, I'm here and ready for your message". This is the SYN-ACK packet. Finally, you send your message knowing that your friend is ready and waiting to receive it. This is the ACK packet.