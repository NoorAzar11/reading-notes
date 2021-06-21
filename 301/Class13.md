## CRUD 

![img](https://camo.githubusercontent.com/8659fc88ec6a71e39d976341a7931d9daa4d9c8885e6cee63e9158d7bb453cdc/68747470733a2f2f7777772e6d696c746f6e6d61726b6574696e672e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031382f30342f63727564616c6c70726f6772616d73646f6974646f776e6c6f61642e706e67)

In your own words, describe what each group of status code represents:

100’s = Continue informational status response code,also it indicates that everything so okay.
200’s = to tell the client that its request was accepted.
300’s =  the request has more than one possible responses.
400’s = its a client error codes,such as wrong URI, missing authentication.
500’s = its an error response code also this error means there is a problem on the server side

- What is a status code 202?
its Created success status response code indicates that the request has succeeded and has led to the creation of a resource

- What is a status code 308?
Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource

- What code would you use if an update didn’t return data to a client?
 its Error 204 => no content 

- What code would you use if a resource used to exist but no longer does?
its Error 307 => Temporary Redirect

- What is the ‘Forbidden’ status code?
its pointed that the server understood the request but refuses to authorize it 


- Why do we need to pull our MongoDB database string out of our server and put it into our .env?
we use it for security purpose 

 - What is middleware?
 ![img](https://slideplayer.com/4804255/15/images/slide_1.jpg)
 
- What does app.use(express.json()) do?
method inbuilt in express to recognize the incoming Request Object as a JSON Object. This method is called as a middleware in your application .

- What does the /:id mean in a route?
 a number which uniquely identifies the route.

- What is the difference beween PUT and PATCH?
![img](https://warroom.rsmus.com/wp-content/uploads/2017/08/table_2.png)

- How do you make a defalut value in a schema?
testschema = mongoose. Schema({ name:{ type:String, required:true, unique:true }, image:{ type:String, required:true }, category:{ type:String }, });

- What is the difference between a status 200 and a status 201?
![img](https://image.slidesharecdn.com/springmvctoiosandtherest-130219141749-phpapp01/95/spring-mvc-to-ios-and-the-rest-15-638.jpg?cb=1361913475)