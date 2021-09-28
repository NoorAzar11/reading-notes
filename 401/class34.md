## Redux - Additional Topics 

![img](https://storage.googleapis.com/indie-hackers.appspot.com/post-images/7eae7c5d32/EcMSE0cxv7YK93SOHy8BtihhcQF2/54c8b668-1398-56cb-4ca6-5d6112a74290.png)

### Review, Research, and Discussion



1. What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

- use redux-thunk and mapDispatchToProps to inject fetchDepartments to the stateless component and implement componentWillMount or similar lifecycle method, to load data - but then I don't need to pass the list via props, as the component would always load data for himself, and I don't want that, because whenever a new component is created the data is fetched from api instead of store
- The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method (probably componentWillMount ) of a Higher Order Component that wraps your ap

2. When using a thunk/async action that dispatches the actual action, which do you export from your reducer?

- When the asynchronous task ends, a callback should manage the outcome of the asynchronous task and appropriately update the state with a positive or negative response, support asynchronous actions by modifying their reducers, i.e. making sure that the reducer intercepting that action starts the asynchronous task and manages its outcome

### Document the following Vocabulary Terms
Term
middleware=> software that enables one or more kinds of communication or connectivity between two or more applications or application components in a distributed network
thunk=>  subroutine used to inject a calculation into another subroutine. Thunks are primarily used to delay a calculation until its result is needed, or to insert operations at the beginning or end of the other subroutine 


### Preparation Materials

- Redux Toolkit (RTK)
he Redux Toolkit package is intended to be the standard way to write Redux logic. It was originally created to help address three common concerns about Redux:
1. Configuring a Redux store is too complicated".
2. I have to add a lot of packages to get Redux to do anything useful".
3. Redux requires too much boilerplate code".
