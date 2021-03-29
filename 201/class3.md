## HTML Lists, CSS Boxes, JS Control Flow

**Html List**

- Numbered Lists 
- Bullet Lists 
- Definition Lists


Ordered Lists: it allows us to give words numbers,and we use <ol> and <li> to do it.

Unordered Lists: it allows to order stuff with bullets shape <ul> <li>.

 Definition Lists:The <dl> tag defines a description list. 

The <dl> tag is used in conjunction with <dt> (defines terms/names) and <dd> (describes each term/name).

Nested Lists it allow us to use <ul> <ol> in the same line to give us two diffrent shape.

![nestedlist](https://s3.amazonaws.com/webucator-how-tos/419.png)

**Box**

1.  Controlling size of boxes
2. Box model for borders, margin and padding
3. Displaying and hiding boxes

The box-sizing property allows us to include the padding and border in an element's total width and height. If you set box-sizing: border-box; on an element, padding and border are included in the width and height: Both divs are the same size now.

div {
  width: 160px;
  height: 80px;
  padding: 20px;
  border: 8px solid red;
  background: yellow;
}

The CSS border properties allow you to specify the style, width, and color of an element's border.
The border-width property specifies the width of the four borders
The width can be set as a specific size (in px, pt, cm, em, etc) or by using one of the three pre-defined values: thin, medium, or thick:

p.one {
  border-style: solid;
  border-width: 5px 20px; /* 5px top and bottom, 20px on the sides */
}

Margins are used to create space around elements, outside of any defined borders

CSS has properties for specifying the margin for each side of an element:

- margin-top
- margin-right
- margin-bottom
- margin-left

p {
  margin-top: 100px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 80px;
}

Padding is used to create space around an element's content, inside of any defined borders.

CSS has properties for specifying the padding for each side of an element:

1. padding-top
2. padding-right
3. padding-bottom
4. padding-left

div {
  padding: 25px 50px 75px 100px;
}


Centering Content : to center the text to the middle

![box](https://lh3.googleusercontent.com/proxy/DxLJsPZmmeaQrDPe2PXtd4ZNLewHSDx-z7bzHY4w8Lg2XvpMjDiZx6kAvNyPAEtyNv9XhUZOwwy-TGHwQPgrrUASWvTmKxBb9DI)

One common use for display: inline-block is to display list items horizontally instead of vertically. The following example creates horizontal navigation links

.nav li {
  display: inline-block;
  font-size: 20px;
  padding: 20px;
}

-Java script we have to use js code with it own js file 
- we have to use <script > tag in html page to load js code .

A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon. 

COMMENTS =>/*js html css */ or //js css html

Variable means anything that can vary. JavaScript includes variables which hold the data value and it can be changed anytime

data type: int ,booleen ,string.

Comparison operators — operators that compare values and return true or false . The operators include: > , < , >= , <= , === , and !== 
