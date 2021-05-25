
# Read: 02 - HTML Text, CSS Introduction, and Basic JavaScript Instructions
## From the Duckett HTML book:
### Chapter 2: “Text” (pp.40-61)

- what markup mean :its tags provide extra meaning and allow browsers to show users the appropriate structure for the page.
- [x] Structural markup
- [x] Semantic markup
 

 ### Structural markup
 |tags|how its look like|exmpel|
 |----|-----------------|------|
 |Headings|\<h1>|\<h1>This is a Main Heading\</h1>\|
 |paragraphs|\<p>|\<p>this paragraphs....\</p>|
 |Bold |\<b>| \<b>bold.\</b>|
 |Italic|\<i>|\<i>Solanum teberosum\</i>|
 |Superscript  |\<sup>|\<p>E=MC\<sup>2\</sup>.\</p>|
 |Subscrip|\<sub>|\<p>2009\<sub>1\</sub>.\</p>|
 |line-breaks|\<br />|\<p>The Earth<br />is big.\</p>|
 |horizontal-rules|\<hr />|\<p>The Earth\</p>\<hr />\<p>is big.\</p>|

 ### Semantic Markup

|tags|how its look like|exmpel|
|----|-----------------|------|
|Strong|\<strong>|\<p>\<strong>my name:\</strong> bushra.\</p>|
|Emphasis|\<em>|<p>I think \<em>Ivy\</em> was the first.\</p>|
|Quotations|\<q>|\<p>I think \<q>Ivy.\</q> was the first.\</p>|
|Author Details|\<address>|\<address>\<p>\<a href="">homer@example.org\</a>\</p>address\</p>\</address>|

### Chapter 10: Ch.10 “Introducing CSS” (pp.226-245)
* CSS is the language we use to style a Web page.
- External -CSS
- internal-css


- CSS Selectors
- [x] Universal Selector / * {}
- [x] Type Selector/h1, h2, h3 {}
- [x] Class Selector/.note {}
- [x] ID Selector/#introduction {}
- [x] Child Selector /li>a {}
- [x] Descendant Selector/p a {}
- [x] Adjacent Sibling Selector//h1+p {}
- [x] General Sibling Selector/ h1~p {}

[for more detials](https://alqudscollege-my.sharepoint.com/:b:/g/personal/advtech_ltuc_com/ETDKUSIt9BxKml92neQqsLoB7WTLFO70vcsmQ8I-HlRTEQ?e=FczW8Q)


## From the Duckett JS book:
### Chapter 2: “Basic JavaScript Instructions” (pp.53-84
### Chapter 4: “Decisions and Loops” only up to the section on switch statements (pp.145-162)
 
*DATA TYPES*
- NUMERIC DATA TYPE  /1.0
- STRING DATA TYPE  / "true"
- BOOLEAN DATA TYPE / true 

### ARRAYS 
**what is arrays**
its type of variable. It doesn't just store one value; it stores a list of values.
- *Create the array*
var colors = ['white',
'black' ,
'custom']; 
 
 **EXPRESSIONS**
  *types of expressions*
 * EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE
 * EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE
 
 ### try to solve this code 
 - [x] var pass = 50;
var score = 90;

var hasPassed = score >= pass;
var el = document .getEl ementByld(' answe r ');
e 1 . t extContent = 'Leve 1 passed: ' + has Passed;

*the answer is* ----
Level passed: true 

- [x] var pass = 50;
var score = 75;
var msg;

if (score >= pass) {
msg = 'Congratulations, you passed!';
} else {
msg = 'Have another go!';
var el = document .getElementByld('answer');
el .textContent = msg; 

*the answer is* ----
Congratulations!
Proceed to the next
round. 

[for more detials](https://alqudscollege-my.sharepoint.com/:b:/g/personal/advtech_ltuc_com/Ecix8R_amQVPhRpnPyJaSmoBleNloBxgtjgnbXS7T9MgoA?e=PPfTVl)



 



 


 
 












