## Authorization/Authentication 

![img](https://lh3.googleusercontent.com/proxy/uQn7wB7Ih2LQ6yoeWDp2x4KZwsPnanLwR-d4hG0AS6DiYASTVyFZVDakO-N_tRnbgxYH1vWb5LrsnM6dTqOsoHrflC3fSg_o-UhbxfyaM4SfYm6MBCcLvr1PIweyV4bCgt43fpKmUNSz7-iiRkG8NpmD-QxiSeBEZ7oTzPY7tkwBmqEkdVhBqEJzHw)

![img](https://s3.ap-south-1.amazonaws.com/afteracademy-server-uploads/authentication-vs-authorization-diff-a7acc34e88679381.png)

### Review, Research, and Discussion 

1. What header(s) are used in authentication and authorization?
- Will The WWW-Authenticate and Proxy-Authenticate response headers define the authentication method that should be used to gain access to a resource. 
-  Its basic HTTP authentication, a request contains a header field in the form of Authorization: Basic <credentials> .

![img](https://media.geeksforgeeks.org/wp-content/uploads/20200420142114/Authentication-header.png)

2.  What is safe to put into a JWT ?
We should always store JWTs inside an httpOnly cookie.

![img](https://www.vaadata.com/blog/wp-content/uploads/2016/12/JWT_tokens_EN.png)
![img](http://19yw4b240vb03ws8qm25h366-wpengine.netdna-ssl.com/wp-content/uploads/Why-Cant-I-Just-Send-JWTs-Without-OAuth-JWT.png)

3. How are JWTs validated ? 

WIll When We receive a JWT from the client, We can verify that JWT with this that secret key stored on the server.

### Document the following Vocabulary Terms :

RBAC =>  Role-based access control it approach to restricting system access to authorized users.

User Roles => Will Its a permission sets that control access to areas and features within the Professional Archive Platform.

JWT Token=> Its a Internet standard for creating data with the optional signature or an optional encryption whose payload holds JSON that asserts some number of claims.

1[img](https://www.aripd.com/assets/img/common/posts/jwt-authentication-flow.svg) 