## Reading: Advanced State with Reducers 

![img](https://miro.medium.com/max/1086/1*a15Fjk16s4CVlfHaTkO73w.png)


### Review, Research, and Discussion 

1. How can we ensure that an effect hook runs only once?
- We Will pass an empty array [] , it just renders the component only once like componentDidMount.

2. Can useState() update more than one state variable at the same time? 
- We can do one setState call and there will only be one render. 
- Unlike the setState in class components, the setState returned from useState doesn’t merge objects with existing state, it replaces the object entirely.

3. Is useState() synchronous? 
- Will useState and setState both are asynchronous, They do not update the state immediately but have queues that are used to update the state object. 
- This is done to improve the performance of the rendering of React components


### Document the following Vocabulary Terms

1. State Hook =>  State of a component is an object that holds some information that may change over the lifetime of the component.and  Hook that allows you to have state variables in functional components , it takes the initial state as an argument and returns an array of two entries. 
2. Component Lifecycle =>  Each component in React has a lifecycle which you can monitor and manipulate during its three main phases: Mounting, Updating, and Unmounting 


- useReducer is a React hook function that accepts a reducer function, and an initial state. ... This hook function returns an array with 2 values. The first one is the state value, and the second value is the dispatch function which is further used to trigger an action with the help of array destructuring

![img](https://helpezee.files.wordpress.com/2021/06/usereducer-hook.jpg?w=640)

![img](https://res.cloudinary.com/practicaldev/image/fetch/s--1ICd6TAL--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/k0z9r0fyhojaytokogf2.JPG)