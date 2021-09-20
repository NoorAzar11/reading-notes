## Reading: <Login /> and <Auth /> 

![img](https://images.ctfassets.net/23aumh6u8s0i/1VvEBUn04IAVjjFWYjWA6q/7d611980c182abbe9a6d89bcd1436a42/new-auth0-universal-login-experience-signup-page)

![img](https://res.cloudinary.com/practicaldev/image/fetch/s--pDTt0xJr--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://bezkoder.com/wp-content/uploads/2020/03/react-jwt-authentication-flow.png)



1. Why is the Context API useful?
- The Context API is a React structure that enables you to exchange unique details and assists in solving prop-drilling from all levels of your application.
![img](https://uploads.toptal.io/blog/image/129071/toptal-blog-image-1549323314875-d6bc9c753a4c9ac2911e8af17732023d.png)
2. Can a component outside of a provider get its context?
- No, it's need to be wrapped between the provider Tag
3. What are some common use cases for using the Context API?
- Change the profile data for the user to be access in any where inside the components and the theme
4. Describe “Context Hell”?
- the React Context hell is the nasty code you get taking advantage of the React Context API

### Document the following Vocabulary Terms
Term
- global state => set of local states which are all concurrent with each other. ... A global state in the time domain is also a global state in the causal domain
![img](https://ihatetomatoes.net/wp-content/uploads/2017/09/02-react-state-local-vs-global.png)
- global context=>context that affects the entire application, and it will share data to everything in the React component tree.
![img](https://www.d11.org/cms/lib/CO02201641/Centricity/Domain/260/Global_Contexts.png)
- provider =>The context provider accepts a value that will be passed to its children. All children components will re-render when the value changes.
- consumer =>  React component that subscribes to context changes in value of the Provider.