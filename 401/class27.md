## Context API - Behaviors 

![img](https://miro.medium.com/max/1400/1*r1hhKt6CRQrYIPES3FlHiQ.png)

- When you have multiple contexts, what component type should you use (class/function) and why?

- function, If two or more context values are often used together, you might want to consider creating your own render prop component that provides both.

- What are some good use cases for using the Context API for global state?

  1. Twilio : Twilio really defines what it means to be API-driven.
  2. Stripe : Stripe is one of the most successful and best known API-driven businesses.
  3. Ebay : Unlike the previous companies, eBay didn’t start out with the intent of being API-driven.
  4. Salesforce : XML APIs have been a part of Salesforce since day one, back in 2000 when it launched.
  5. Rovi :Rovi is definitely the oldest company on the list, founded as Macrovision in 1983.


  - How can you best test context? 
  - The best way to test Context is to make our tests unaware of its existence and avoiding mocks


## Document the following Vocabulary Terms
1. context=> method to pass props from parent to child component(s), by storing the props in a store(similar in Redux) and using these props from the store by child component(s) without actually passing them manually at each level of the component tree
2. useContext()=> create common data that can be accessed throughout the component hierarchy without passing the props down manually to each level
3. static context=> which wraps our component with PureComponent shallow comparison logic while also allowing us to pass references from our context 

![img](https://i1.wp.com/www.techomoro.com/wp-content/uploads/2021/01/without-context-and-with-context.png?resize=640%2C341&ssl=1)