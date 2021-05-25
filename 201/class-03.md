# Read: 03 - HTML Lists, CSS Boxes, JS Control Flow
## From the Duckett HTML book:

- Chapter 3: “Lists” (pp.62-73)
- Chapter 13: “Boxes” (pp.300-329)

*typeof text*
- Ordered lists
- Unordered list
- Definition lists

 ###  Ordered lists 
 *Ordered lists use numbers.*
(\<ol> \<li>)

- exmpel

\<ol>

\<li>Heat milk, butter and nutmeg\</li>

\<li>Drain potatoes and mash\</li>

\<li>Mix in the milk mixture\</li>

\</ol>

 - result
<ol>
<li>Heat milk, butter and nutmeg</li>
<li>Drain potatoes and mash</li>
<li>Mix in the milk mixture</li>
</ol>


###  unordered-lists
*Unordered lists use bullets.*
(\<ul>
 \<li>)

- exmpel

\<ul>

\<li>Heat milk, butter and nutmeg\</li>

\<li>Drain potatoes and mash\</li>

\<li>Mix in the milk mixture\</li>

\</ul>


 - result
<ul>
<li>Heat milk, butter and nutmeg</li>
<li>Drain potatoes and mash</li>
<li>Mix in the milk mixture</li>
</ul>


###  Definition Lists
(\<dl>
 \<dt> \<dd>)

- exmpel

\<dl>
\<dt> one \</dt>

\<dd>Heat milk, butter and nutmeg\</dd>

\<dt> two \</dt>

\<dd>Drain potatoes and mash\</dd>

\<dt> three \</dt>

\<dd>Mix in the milk mixture\</dd>

\</dl>


- result
<dl>
<dt> one </dt>

<dd>Heat milk, butter and nutmeg</dd>

<dt> two</dt>

<dd>Drain potatoes and mash</dd>

<dt> three </dt>

<dd>Mix in the milk mixture</dd>

</dl>

### nested-lists
*You can put a second list inside an \<li> element to create a sublist or nested list.*


## Boxs


* Box Dimensions
*width, height*

* Limiting Width
*min-width, max-width*

* Limiting Height
*min-height, max-height*

- overflow
   - *hidden*
    - *scroll*

* Border, Margin & Padding

*The padding and margin properties are very helpful in adding space between various items on the page.*

- border-width
  - *thin*
   - *medium*
    - *thick*


*The border-width property is used to control the width of a border*

* border-style
* border-color


* padding

*allows you to specify how much space should appear between the content of an element and its border*

* margin

*controls the gap between boxes.*

* display

*The display property allows you to turn an inline element into a block-level element or vice versa, and can also be used to hide an element from the page*

* visibility

*The visibility property allows you to hide boxes from users but It leaves a space where the 
element would have been.*

*  box-shadow

*allows you to add a drop shadow around a box*

* border-radius

*The value indicates the size of the radius in pixels.*

## From the Duckett JS book:

### Review from Reading 02 
- Chapter 2: “Basic JavaScript Instructions” (pp.70-73)
- Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)


**ARRAYS**

type of variable, It doesn't just store one value; it stores a list of values. 

* colors= ['white',
'black',
'custom'];


- VALU ES IN ARRAYS
  - NUMBERING ITEMS IN AN ARRAY
   - ACCESSING ITEMS IN AN ARRAY
    - NUMBER OF ITEMS IN AN ARRAY 

    **Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).**


*Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>) are used to compare two operands.*
 

**SWITCH STATEMENTS**

switch (level) {
case 'One ':
title= 'Level 1 ' ;

break;

case 'Two':
tit 1 e = ' Level 2 ' ;

break;

case ' Three' :
title = 'Level 3' ;

break ;

default :
title= 'Test';

break; 

**LOOPS**

- **FOR LOOPS**

*A for loop is often used to loop through the items in an array*

- exampel


var scores= [24. 32, 17]; 
var arraylength scores.l ength; 
var roundNumber = O;
var msg ''; 
var i ; 

for (i = O; i < arraylength; i++) { 

    roundNumber = (i + l); 

    msg += 'Round ' + roundNumber + ' : '; 

    msg += scores[i] + '<br / >' ; }

    document .getElementByid( 'answer') .i nnerHTML msg; 

- result

Round 1: 24

Round 2: 32

Round 3: 17 

- **WHILE LOOPS**
- **DO WHILE LOOPS**

*The key difference between a while loop and a do while loop is that the statements in the code block come before the condition. This means that those statements are run once whether or not the condition is met.*


- example

var i = l;//Set counter to 1

var msg : '': //Message 

//Store 5 times table in a variable

do {

msg += i + ' x 5 = ' + (i * 5) + '<br I>' ;s

i++;

} wh il e ( i < 1) ;

// Note how this is already 1 and it still runs

document .getEl ementByld(' answer').innerHTML = msg; 

- result

lx5=5 



## quize

try to solve it 

var table = 3; 

var operator= 'addition';

var i = 1;

var msg = ' ' ;

if (operator=== 'addition')

whi l e (i < 11) {

msg += i + ' + ' + table +' = ' + (i +table)+ '/<br I>'; 

i++; }

while ( i < 11) {

msg += i + ' x ' + table + ' =' + (i *table) + '<br I> ';

i++; }}

var el = document.getElementByid{'bl ackboard');
el .innerHTML = msg;

**here are the books for the read**

[HTML AND CSS](https://alqudscollege-my.sharepoint.com/:b:/g/personal/advtech_ltuc_com/ETDKUSIt9BxKml92neQqsLoB7WTLFO70vcsmQ8I-HlRTEQ?e=FczW8Q)

[JavaScrip](https://alqudscollege-my.sharepoint.com/:b:/g/personal/advtech_ltuc_com/Ecix8R_amQVPhRpnPyJaSmoBleNloBxgtjgnbXS7T9MgoA?e=PPfTVl).




















 

























































