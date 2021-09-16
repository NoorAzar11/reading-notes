## Context API

- The Context API is a React structure that enables you to exchange unique details and assists in solving prop-drilling from all levels of your application.

![img](https://res.cloudinary.com/practicaldev/image/fetch/s--f75vcUWo--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/pyhm0w8sbuo75op77md2.jpg)


### Review, Research, and Discussion


1. Describe use cases useState() vs useReducer() ?

- useState is a Basic Hook for managing simple state transformation and useReducer is an Additional Hook for managing more complex state logic, it is worth noting that useState uses the useReducer internally. This implies that you could use useReducer for everything you can do with useState. 

- useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

2. Why do custom hooks need the use prefix?
- The name of any custom hook should begin with use. This convention indicates to developers that hooks are used within the file/custom hook. 

3. What do custom hooks usually do?
- Custom hooks allow us to have cleaner functional components, remove logic from the UI layer, and prevent code duplication by bringing common use cases to reusable hooks 
4. Using any list of custom hooks, research and name one that you think will be useful in your applications?\
- useScript React hook to dynamically load an external script and know when its loaded ,useScript is a hook for loading (and notifying when they’re loaded) external scripts, dynamically .

5. Describe how a hook that fetches API data might work ?
 - hook might take in a url, a method, and a body. Using axios or something similar, useState and possibly useEffect, an API call can be made based on and using the parameters passed in and then an objects state could be ‘set’ based on the results of the API call

 - reducer => NgRx are responsible for handling transitions from one state to the next state in your application. Reducer functions handle these transitions by determining which actions to handle based on the action's type .