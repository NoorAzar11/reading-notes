## HTML Links, JS Functions, and Intro to CSS Layout

###  Links

- Creating links between pages
- Linking to other sites
- Email links

** How to links between pages in HTML? **

** Linking to other Web Pages Linking in HTML code is done with the anchor tag, the <A> tag. The letter "A" in the tag is then followed by an attribute. For a link to another web page, the "A" is followed by "HREF". **

ex: <a href="http://www.metacritic.com">

how Linking to other sites ?
- <a href="index.html">Home</a></li>
 
 - <a href="about-us.html">About</a></li>  
 
what is a directory structure?
 
 ** a directory structure is the way an operating system 's file system and its files are displayed to the user. Files are typically displayed in a hierarchical tree structure. **

 how to link email to page?
 The basic code to create an email link in HTML looks like this: <a href="mailto:

How to open a link in a new window?

In order to open a link in a new window you just need to add the target="_blank" attribute to your anchor link, like this: In the given example, when a visitor clicks on the hyperlink, it will open in a new window or tab.

<a href="http://www.imdb.com" target="_blank">

### Layout

 1. Controlling the position of elements
2. Creating site layouts
3. Designing for different sized screens

There are five different position values:

- static : elements are not affected by the top, bottom, left, and right properties ex.position: static;.
- relative position: relative;
- fixed A fixed element does not leave a gap in the page where it would normally have been located,position: fixed; .
- absolute position: absolute;
- sticky An element with position: sticky; is positioned based on the user's scroll position.


HTML primitives. Like tables, grid layout enables an author to align elements into columns and rows

Grid Layout
The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.

<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  </div>

![Grid layout](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/8d374c1e-228a-47e8-be5b-10fa1f4d40c8/mrh-css-grid-fig-01-large-opt.png) 

Grid Columns
The vertical lines of grid items are called columns.

Grid Gaps
The spaces between each column/row are called gaps

grid-column-gap
grid-row-gap
grid-gap

 ** Designers keep pages within 960-1000 pixels wide, 
and indicate what the site is about within the top 600 
pixels (to demonstrate its relevance without scrolling)**

### Functions, Methods, and Objects

A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output.

JavaScript a function allows you to define a block of code, give it a name and then execute it as many times as you want. A function can be defined using function keyword and can be executed using () operator. A function can include one or more parameters.

![functions](https://miro.medium.com/max/2000/1*KbE6qWmCQg5isyMRQzwfpg.png)