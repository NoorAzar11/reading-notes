##  Redux - Asynchronous Actions
- Redux Thunk is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store's dispatch method, which is then used to dispatch regular synchronous actions inside the function's body once the asynchronous operations have been completed.

![img](https://miro.medium.com/max/638/1*gzSOKTC2V-mQhAJ-fc0qIA.jpeg)

![img](https://res.cloudinary.com/practicaldev/image/fetch/s--Vls3yFQQ--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9xlfajv7h2avobyv2bry.jpeg)

- Asynchronous communication means communication which happens 'out of sync' or in other words; not in real-time.

- That means asynchronous communications takes place as a less time-sensitive interchange between communicating parties. For example, an email to a colleague would be classed as asynchronous communication.

### Review, Research, and Discussion


1. How granular should your reducers be?
- There should be a separate reducer function for each slice of data. They are combined before being put into the store

2. Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched?
- This is a Con because you may fire off reducers that you did not intend

3. Name a strategy for preventing the above?
- You can use more specific names that represent the reducer and data want to change

### Document the following Vocabulary Terms
Term
store=>holds the whole state tree of your application. The only way to change the state inside it is to dispatch an action on it
combined reducers=>  helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.