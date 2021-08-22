##  Socket.io 

- Socket.IO Its a library that enables real-time, bidirectional and event-based communication between the browser and the server.

![img](https://miro.medium.com/proxy/1*3C1OmIZj_S_VUCLIhWRhVw.png)

1. What is the benefit of transforming data into packets?
Its transfer file data fast and efficient manner over the network and minimize the transmission latency, and then data broken into peices of variable length.

![img](https://cdn.ttgtmedia.com/rms/onlineimages/whatis-packet_structure_half_column_mobile.png)

2. UDP is often refereed to as a connectionless protocol. Why is this?
- UDP => is a connectionless protocol and its known as datagram protocol because it is analogous to sending a letter where you don't acknowledge receip.
![img](https://slidetodoc.com/presentation_image/5a456252222746361e9b6fa886d38a88/image-38.jpg)

3. Can a socket server application have multiple socket connections?
- It has Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs.

4. Can a socket connection application be connected to multiple socket servers?
- yes it is posiible if we make a lot of connections in a very short time.

5. Can an application be both a socket server and a socket connection? 
- We are willing to use two different ports, because sockets won't be using the same port at the same time.
![img](https://www.wut.de/pics/misc/e-58www-16-grus-000.gif)

### Document the following Vocabulary Terms :
- Observer Pattern=>  it is concerned about communication between objects
- Listener=>  its events that cause Function objects
- Event Handler => its Handle and verify user input, user actions, and browser action
- Event Driven Programming=> its declares functions and then simply waits for the event to occur.
- Event Loop=> its allows Node. js to perform non-blocking I/O operations
- Event Queue=> support concurrency via the concept of event and callbacks
- Call Stack=> its call stack is a LIFO (Last In, First Out) stack
- Emit/Raise/Trigger=> in event-driven programming, emit sends a message to trigger a response and raise an event 
- Subscribe=> dom events in browser or node.js events
- database => its organized collection of structured information, or data, typically stored electronically in a computer system 


### What is meant by WebSocket? 
- its alternative to HTTP communication in Web Applications.

![img](https://www.baeldung.com/wp-content/uploads/2019/04/HTTP-Connection.jpg)
![img](https://developers.refinitiv.com/content/dam/devportal/articles/how-to-implement-elektron-websocket-api-javascript/rebrand/webworker_1.png)