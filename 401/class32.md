## Redux - Combinereducers 

- The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore . The resulting reducer calls every child reducer, and gathers their results into a single state object.

![img](https://i.ytimg.com/vi/EKsoj96HQGY/maxresdefault.jpg)

![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSCCY5o9JfNb-vDx3xkfKzHHnEY-9741VVUog&usqp=CAU)

## Review, Research, and Discussion

1. Why choose Redux instead of the Context API for global state?

- Redux is much more powerful and provides a large number of features that the Context Api doesn't provide, Also, React Redux uses context internally but it doesn’t expose this fact in the public API. So you should feel much safer using context via React Redux than directly because if it changes, the burden of updating the code will be on React Redux instead developer responsibility

2. What is the purpose of a reducer?
- takes the previous state and an action, and returns the next state

3. What does an action contain?
- a type property and any other data that it needs to describe the action

4. Why do we need to copy the state in a reducer?
- change values inside an object and we want to know if something has changed, we'd have to make a full copy so we can store individual properties, and then compare each property of the new and old object to determine what, if anything, has change.


### Term

1. immutable state=> state that cannot be changed

2. time travel in redux=>  ability to move back and forth among the previous states of an application and view the results in real time 
3. action creator=> function that returns an action object   
4. reducer=> function that receives the current state and an action object, decides how to update the state if necessary, and returns the new state
5. dispatch=> only way to update the state is to call store.dispatch() and pass in an action object.
