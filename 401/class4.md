#  Express REST API

- Express is a perfect choice for a server when it comes to creating and exposing APIs,also  to communicate as a client with your server application. 

## Name 3 real world use cases where you’d want to change the request with custom middleware:
1. parameteres validation
2. Data Manegment 
3. Error Handling 

## True or false: The route handler is middleware? 
- Its a false because route handler is code and it will take the requset and response without using mddleware ,so middleware we use it to change the shape of the req and res. 

## In what ways can a middleware function end the process and send data to the browser?
 - We can send data to the browser using next function ,also we can process by get an internal error like 500 error ,also we can use res.send(),res.json().

 ## At what point in the request lifecycle can you “inject” middleware?
  -  We can inject the middleware after creating the request and before we send the response.
  ![img](https://loopback.io/pages/en/lb4/imgs/middleware.png)

  ## What can cause express to error with “Request headers sent twice, cannot start a second response”
  - When we have more than one response that we send to our client


  ## Document the following Vocabulary Terms 

### Term
1. Middleware =>  type of computer software that provides services to software applications .
2. Request Object =>  represents the HTTP request and has properties for the request query string, parameters, body, HTTP headers.
3. Response Object => its an object which communicates between the server and the output which is sent to the client
4. Application Middleware => its a software that provides services beyond those provided by the operating system
5. Routing Middleware => its a middleware that works on router level router.use 
6. Test Driven Development => that bound to an instance of express.Router(). 
7. Behavioral Testing => to test the  the external behaviour of the program

### Review: ES6 Classes
- its  JavaScript pattern of simulating class-like inheritance hierarchies using functions and prototypes.

![img](https://miro.medium.com/max/700/1*yiS2QvVKIpYCb0fqvrsXZQ.png) 


### Using Express Routing 
- its refers to determining how an application responds to a client request to a particular endpoint, which is a URI (or path) and a specific HTTP request method (GET, POST).

- Routing methods can have more than one callback function as arguments .