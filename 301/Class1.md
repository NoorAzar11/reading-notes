### Introduction to React and Components

![img](https://www.innoraft.com/sites/default/files/styles/blog_original_size/public/2019-09/Screenshot%20from%202019-09-17%2014-05-24.png)

## React
  a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”.

### A component takes in parameters, called props (short for “properties”), and returns a hierarchy of views to display via the render method.
* Square
* Board
* Game

* A component takes in parameters, called props (short for “properties”), and returns a hierarchy of views to display via the render method.
1. Square
1. Board
1. Game

# Why JSX?

### React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.

### Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both. We will come back to components in a further section, but if you’re not yet comfortable putting markup in JS, this talk might convince you otherwise.

### React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.
# Components and Props:
Components let you split the UI into independent, reusable pieces, and think about each piece in isolation.

 # Function and Class Components:
 This function is a valid React component because it accepts a single “props” (which stands for properties) object argument with data and returns a React element. We call such components “function components” because they are literally JavaScript functions.

 # Rendering a Component:
 When React sees an element representing a user-defined component, it passes JSX attributes and children to this component as a single object. We call this object “props”.