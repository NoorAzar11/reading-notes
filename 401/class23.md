## Component Lifecycle / useEffect() Hook

- By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we'll refer to it as our “effect”), and call it later after performing the DOM updates.
![img](https://i.stack.imgur.com/7q1jC.jpg)

### Review, Research, and Discussion 

1. Why do we not need more .html pages in a multi-page React app?

 - Multi-page apps, we get back multiple HTML pages, where each page has content for given Router.
-  Multi-page apps, we only use React to create widgets.
- Multipage apps, we split up our components but a lot of pages are going to be normal HTML pages, and widgets we dump in like an Image gallery that is managed by React, so the entire page is not under React control.
- Because we build a react frontend client side that is a Single page Application, it's rendering the component that will render on the page not by render a new page.

2. If we wanted a component to show up on every page, where would we put it and why?
Outside the <BrowserRouter/>
Inside the <BrowserRouter />, outside a <Route />
Inside a <Route /> ?

- Inside the <BrowserRouter />, outside a <Route />

3. What does routing do with the components that were rendered when a new route is requested?

-  renders the appropriate user interface when the current location matches the route’s path. 
-  The component prop defines the React element that will be returned by the Route when the path is matched. This React element is created from the provided component using React.createElement.

![img](https://files.speakerdeck.com/presentations/41bce6e8f4964c7abb5bdd2682ace335/slide_50.jpg)

4. What does props.children contain?
-  children is a special property of React components which contains any child elements defined within the component, e.g. the divs inside Example above. {this.props.children} includes those children in the rendered result.
- props. children does is that it is used to display whatever you include between the opening and closing tags when invoking a component. This component contains an <img> that is receiving some props and then it is displaying {props
![img](https://soshace.com/wp-content/uploads/2019/08/React-Children-Cheat-Sheet.png)

5. How do useState() and this.setState() differ?

- The setState function is used to handle the state object in a React class component. -
-  setState is merging the previous state with the new one, it means that you dont have to pass the full state object every time you want to change some part of the state. React will update given properties and won't touch the rest. The useState's updater rewrites a previous state with a new one and it does not perform any merging. Its just replacement instead of merging.


### Document the following Vocabulary Terms
Term 
State Hook =>  State of a component is an object that holds some information that may change over the lifetime of the component.and  Hook that allows you to have state variables in functional components , it takes the initial state as an argument and returns an array of two entries. 

Mounting and Un-Mounting => Mounting is the process of outputting the virtual representation of a component into the final UI representation (e.g. DOM or Native Components). & Un-Mounting: This method is called just before the component gets destroyed. Any clean up statements should be executed inside this method.

- Effects hook
![img](https://miro.medium.com/max/1838/1*yJvDmCk1XcM-3ZVkBBItvw.png)