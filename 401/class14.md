##  Message Queues :

- A message queue is a form of asynchronous service-to-service communication used in serverless and microservices architectures.(from google).

-  Messages are stored on the queue until they are processed and deleted. Each message is processed only once, by a single consumer. (from google).

![img](https://www.cloudamqp.com/img/blog/thumb-mq.jpg)

![img](https://miro.medium.com/max/976/1*cCyPNzf95ygMFUgsrleHtw.png)

### Review, Research, and Discussion :

1. What does it mean that web sockets are bidirectional? Why is this useful?
- Client and server are connected by two ways (from client to server and from server to client),and its useful in increasing speed and realtime capability .

2. Does socket.io use HTTP? Why?
- socket.io server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js  (from google).

3. What happens when a client emits an event? 
- emit an event from your client, use the emit function on the socket object. To handle these events, use the on function on the socket object on your server. Sent an event from the client!

![img](https://image.slidesharecdn.com/socket-160115210006/95/socketio-part-1-15-638.jpg?cb=1452891884)

4. What happens when a server emits an event?
- all listening clients will execute the handeler for that event.

5. What happens if a client “misses” an event?
- Will Event Handler will be excuted.

6. How can we mitigate this?
- We can use message queue.

### Document the following Vocabulary Terms 
1. Socket=> Its a one endpoint of a two-way communication link between two programs running on the network.
2. Web Socket=>its  computer communications protocol, providing full-duplex communication channels over a single TCP connectio
3. Socket.io=> its enables real-time, bidirectional and event-based communication. It works on every platform, browser or device, focusing equally on reliability and speed
4. Client=> its piece of computer hardware or software that accesses a service made available by a server as part of the client–server model of computer networks
5. Server => a computer or system that provides resources, data, services, or programs to other computers
6. OSI Model=>Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system
7. TCP Model=> It stands for Transmission Control Protocol/Internet Protoco
8. TCP=> stands for Transmission Control Protocol a communications standard that enables application programs and computing devices to exchange messages over a network
9. UDP=> User Datagram Protocol (UDP) is a lightweight data transport protocol that works on top of IP. 
10. Packets=>basic units of communication over a TCP/IP network. Devices on a TCP/IP network divide data into small pieces, allowing the network to accommodate various bandwidths

### Socket.io Chat Example

![img](https://codecanyon.img.customer.envatousercontent.com/files/253263250/chatApp_thumb.jpg?auto=compress%2Cformat&q=80&fit=crop&crop=top&max-h=8000&max-w=590&s=cd32c927f5b4652be95399c5e3a7cd4a)

![img](https://image.slidesharecdn.com/slides-150328114547-conversion-gate01/95/introduction-to-development-of-multiplayer-html5-games-with-socketio-13-638.jpg?cb=1427687994)