## Bearer Authorization 

- its a HTTP authentication scheme that involves security tokens called bearer tokens,asldo called token authentication.

![img](https://files.readme.io/a444a2d-Screenshot_2019-11-14_at_09.58.01.png)
![img](https://lbadri.files.wordpress.com/2012/09/untitled4.png?w=700)

### Review, Research, and Discussion

- Write the following steps in the correct order:
1. Receive access token
2. Redirect to a third party authentication endpoint
3. Register your application to get a client_id and client_secret
4. Make a request to a third-party API endpoint
5. Ask the client if they want to sign in via a third party
6. Receive authorization code
7. Make a request to the access token endpoint

### the right steps : 

  1. Register your application to get a client_id and client_secret.
  2. Ask the client if they want to sign in via a third party.
  3. Redirect to a third party authentication endpoint.
  4. Make a request to a third-party API endpoint
  5. Receive authorization code.
  6. Make a request to the access token endpoint.
  7. Receive access token. 


### What can you do with an authorization code? 
- client will get back with the auth code and client credentials will request for a token.

### What can you do with an access token?
- Will it can be used as a applications use to make API requests on behalf of a user.

### What’s a benefit of using OAuth instead of your own basic authentication?
1. It allows you to read data of a user from another application.
2. It supplies the authorization workflow for web, desktop applications, and mobile devices.
3. Is a server side web app that uses authorization code and does not interact with user credentials.


### Term :

Client ID =>  Its a unique identifier for a browser–device pair that helps Google Analytics link user actions on a site.
Client Secret=> secret known only to your application and the authorization server.
Authentication Endpoint=> Use the authentication endpoint to specify an endpoint that is called to obtain an access token which can then be used in the subsequent password update callouts
Access Token Endpoint=> token endpoint is an HTTP endpoint that micropub clients can use to obtain an access token given an authorization code.
API Endpoint=> endpoint is one end of a communication channel.
Authorization Code=> alphanumeric password that authorizes its user to purchase, sell or transfer items,
Access Token=>The access token represents the authorization of a specific application to access specific parts of a user’s data.


### Preparation Materials :

- JWTs Explained => 
![img](http://19yw4b240vb03ws8qm25h366-wpengine.netdna-ssl.com/wp-content/uploads/Why-Cant-I-Just-Send-JWTs-Without-OAuth-JWT.png)

![img](https://miro.medium.com/max/1400/1*WrMX8PcUWaRwF00deECtzQ.png)