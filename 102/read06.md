# CSS HTML Color

#### To set the background color in HTML, use the style attribute. The style attribute specifies an inline style for an element. The attribute is used with the HTML <body> tag, with the CSS property background-color.
 HTML5 do not support the <body> tag bgcolor attribute, so the CSS style is used to add background color.

##### To set the font color in HTML, use the style attribute. The style attribute specifies an inline style for an element. The attribute is used with the HTML <p> tag, with the CSS property color. 
HTML5 do not support the <font> tag, so the CSS style is used to add font color.

What is inherit in HTML?

The inherit keyword specifies that a property should inherit its value from its parent element. 
The inherit keyword can be used for any CSS property, and on any HTML element.


##List of CSS Properties that are Inherited :
<ul>
<li>border-collapse.<li/>
<li>border-spacing.<li/>
<li>caption-side.<li/>
<li>color.<li/>
<li>cursor.<li/>
<li>direction.<li/>
<li>empty-cells.<li/>
<li>font-family.<li/>

<p> div (short for division) allows us to divide our page into different sections, 
to position this sections. Divs are very useful. The change might not be the most visual one, doesn't make it less useful. 
if we only used text, everything would just be from top to bottom. </p>

<div> element with a class called page inherits the padding size from the CSS rule that 
 applies to the <body> element.

RGP in HTML ? 
Each parameter (red, green, and blue) defines the intensity of the color with a value between 0 and 255. This means that there are 256 x 256 x 256 = 16777216 possible colors!
 For example, rgb(255, 0, 0) is displayed as red, because red is set to its highest value (255), and the other two (green and blue) are set to 0.

/* color name */
h1 {
color: DarkCyan;}
/* hex code */
h2 {
color: #ee3e80;}
/* rgb value */
p {

color: rgb(100,100,90);} 

Name  |	Hex Code   |	RGB Code
Green |	#008000	rgb|(0, 128, 0)
Aqua  |	#00FFFF	rgb|(0, 255, 255)
Teal  |	#008080	rgb|(0, 128, 128)
Blue  |	#0000FF	rgb|(0, 0, 255)

CSS backgroun color ?
body {
background-color: rgb(200,200,200);}
h1 {
background-color: DarkCyan;}
h2 {
background-color: #ee3e80;}
p {
background-color: white;}


CSS3: HSL & HSLA

### hue
This is expressed as an angle (between 0 and 360 degrees).

### saturation
This is expressed as a percentage.

### lightness
This is expressed as apercentage with 0% being white, 50% being normal, and 100% being black

### alpha
This is expressed as a number between 0 and 1.0. For example, 0.5 represents 50% transparency, and 0.75
represents 75% transparency. 

CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.


### A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value,
 but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output.


