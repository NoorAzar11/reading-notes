# JavaScript supports different kinds of loops:

1. for - loops through a block of code a number of times
2. for/in - loops through the properties of an object
3. for/of - loops through the values of an iterable object
4. while - loops through a block of code while a specified condition is true
5. do/while - loops through a block of code once, and then repeats the loop while a specified condition is true.

# Parameter Values

1. var	Required -> A variable that iterates over the properties of an object
2. object	Required-> The specified object that will be iterated

<h4> CALCULAT E ANO WRITE OUT THE EX PIRY DETAILS FOR THE OFFER:

 <ul>
<li>var expiryMsg; II Message displ ayed t o users </li>
<li>var today ; II Today's date </li>
<li>var el Ends ; II The element that shows the message about the offer ending </li>

<h4> function offerExp ires(today):

#### II Decl are variables within the function for l ocalscope

var weekFromToday, day, date, month, year, dayNames, monthNames;

### II Add 7 days time (added i n mil liseconds)
weekFromToday =new Dat e(today .getTime () + 7 * 24 * 60 * 60 * 1000) ;
II Create arrays to hol d t he names of days I months

dayNames = [' Sunday' , 'Mo nday' , 'Tuesday ' , 'Wednesday ', 'Thursday' ,
0 ' Friday', 'Saturday '] ;

mont hNames =['January', ' February', 'March', 'Apri l ', 'May ' , 'June ' ,
0 'Jul y' , 'August ' , 'September' , 'October' , ' November' , 'December'] ; 

how to  Collect the parts of date :
1. day = dayNames [weekFromToday . getOay ()];
2. date= weekFromToday .getOate();
3. month= mont hNames[wee kFromToday.getMonth()] ;
4. year= weekFromToday .getFullYear() ; 

how to  Create the message:
1. expi ryMsg = 'Offer expires next ' ;
2. expi ryMsg += day + ' <br I>( ' +date+ ' ' +month+ ' ' +year + ')';
return expiryMsg;  



// = Vs == VS === in JavaScript

1. <b>= in JavaScript is used for assigning values to a variable. </b>

2. <b>== in JavaScript is used for comparing two variables, but it ignores the datatype of variable.</b>

3. <b> === is used for comparing two variables, but this operator also checks datatype and compares two values.
</b>
Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS. 
3 === var1. 
Strict not equal ( !== )Returns true if the operands are of the same type but not equal, or are of different type



### In JavaScript we have the following conditional statements:
<ol>
<li>Use if to specify a 
block of code to be executed, if a specified condition is true.</li>
<li>Use else to specify a block of code to be executed, if the same condition is false.</li>
<li>Use else if to specify a new condition to test, if the first condition is false.</li>