## Problem Domain, Objects, and the DOM

### Object Literals

- object Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.

- object: is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made.

- Objects are variables too. But objects can contain many values.
var car = {type:"Fiat", model:"500", color:"white"};

- JavaScript objects are containers for named values called properties or methods.
- var person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};


Property	Property Value
firstName	John
lastName	Doe
age	50
eyeColor	blue

Property	Property Value
firstName	John
lastName	Doe
age	50
eyeColor	blue
fullName	function() {return this.firstName + " " + this.lastName;}

### Document Object Model (DOM)

>The Document Object Model (DOM) specifieshow browsers should create a model of an HTMLpage and how JavaScript can access and update thecontents of a web page while it is in the browser window. 

![DOM](https://techinsight.com.vn/wp-content/uploads/2020/08/1-2.png)

>HTML DOM methods are actions you can perform (on HTML Elements).

> HTML DOM properties are values (of HTML Elements) that you can set or change.


The DOM Programming Interface

1. The HTML DOM can be accessed with JavaScript (and with other programming languages).

2. In the DOM, all HTML elements are defined as objects.

3. The programming interface is the properties and methods of each object.

4. A property is a value that you can get or set (like changing the content of an HTML element).

5. A method is an action you can do (like add or deleting an HTML element).

>To add a new element to the HTML DOM, you must create the element (element node) first, and then append it to an existing element.

>To add text to the <p> element, you must create a text node first. This code creates a text node:

>> var node = document.createTextNode("This is a new paragraph.");

>>The appendChild() method in the previous example, appended the new element as the last child of the parent.

>>>Removing Existing HTML Elements To remove an HTML element, use the remove() method.

<div>
  <p id="p1">This is a paragraph.</p>
  <p id="p2">This is another paragraph.</p>
</div>

Find the element you want to remove:

var elmnt = document.getElementById("p1");
Then execute the remove() method on that element:

elmnt.remove();


#### The HTMLCollection Object:

- The getElementsByTagName() method returns an HTMLCollection object.

- An HTMLCollection object is an array-like list (collection) of HTML elements.

- HTML HTMLCollection Length The length property defines the number of elements in an HTMLCollection.

#### The HTML DOM NodeList Object

1. A NodeList object is a list (collection) of nodes extracted from a document.

2. A NodeList object is almost the same as an HTMLCollection object.

3. Some (older) browsers return a NodeList object instead of an HTMLCollection for methods like getElementsByClassName().

4. All browsers return a NodeList object for the property childNodes. 

5. Most browsers return a NodeList object for the method querySelectorAll().

var myNodeList = document.querySelectorAll("p");

6. A node list is not an array!

7. A node list may look like an array, but it is not.

8. You can loop through the node list and refer to its nodes like an array.

9. However, you cannot use Array Methods, like valueOf(), push(), pop(), or join() on a node list.
