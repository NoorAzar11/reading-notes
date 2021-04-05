## More CSS Layout

### Layout CSS

CSS treats each HTML elements as if it is in its own box,the bok will inline box or a block-level.

- inline box : <img> <b> <i>
- block-level:<h1> <p> <ul> <li>

#### Controlling the Position of Elements

- Normal flow.
- relative position.
- Absolute positioning .
- fixed.

 Normal flow is nothing but the way in which the elements are positioned in a web browser.

 relative element is positioned according to the normal flow of the document, and then offset relative to itself based on the values of top, right, bottom, and left.

absolute element is removed from the normal document flow, and no space is created for the element in the page layout.

 Fixed element is removed from the normal document flow, and no space is created for the element in the page layout.

sticky element is positioned according to the normal flow of the document.

![Normal flow](https://cdn.mos.cms.futurecdn.net/7vpUPMSbPfhxiUNYj5XnE6.jpg)

 page size screen sizes and display resolutions of around 960-1000 pixels wide .

 Fixed Width Layouts created doesnt  change size as the user increasesor decreasesthe size of their web page.

Liquid layouts define layout regions that both resize with text, and reflow as needed to accommodate on-screen display.

 how to show a Grid in CSS ?
We have to define a container element as a grid with display: grid , set the column and row sizes with grid-template-columns and grid-template-rows , and then place its child elements into the grid with grid-column and grid-row .

 Grids help create professional and flexible designs.


![Grid](https://miro.medium.com/max/3392/1*ia4V5qfk6Ki3iWIn-SmErw.png)