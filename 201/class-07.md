# Readings : Object-Oriented Programming, HTML Tables
## Read

- [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)
- [From the Duckett HTML book:](https://alqudscollege-my.sharepoint.com/:b:/g/personal/advtech_ltuc_com/ETDKUSIt9BxKml92neQqsLoB7WTLFO70vcsmQ8I-HlRTEQ?e=FczW8Q)

Chapter 6: “Tables” (pp.126-145)
- [From the Duckett JS Book:](https://drive.google.com/file/d/1L74jU_Js5jSjbi2hg87TNyT-hnVkoXwJ/view)

Chapter 3: “Functions, Methods, and Objects” (pp.106-144)




### Domain Modeling
*Domain modeling is the process of creating a conceptual model in code for a specific problem*

**Generate random numbers**

- Math.random()

- EpicFailVideo.prototype.generateRandom = function(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}


### Tables

*A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.*


* Basic Table Structure

\<table>--- add tables ,\<tr>--- created row, \<td>----created cells 


* table headings

\<th>-----created cells if it is a header

* Spanning ColumnS

The colspan attribute can be used on a \<th> or \<td> element

* Spanning Rows ------for make cells of a table span more than one row
or column

The rowspan attribute can be used on a \<th> or \<td> element to indicate how many rows a cell should span down the table.

* Long Tables

\<thead> ,\<tbody>,\<tfoot>



### Functions, Methods, and Objects

- Functions allow you to group a set of related statements together that represent a single task.


- to update the value of property -----use dot notation

object name.prop mame= 'prop value';

- to delete the value ------ use delete key word

delete object name.prop mame;


- CREATING MANY OBJECTS: CONSTRUCTOR NOTATION

*Object constructors can use a function as a template for creating objects.*

1- create the template with the object's properties and methods.

function object name (prop1, prop2, prop3) {
th i s . prop1 = prop1 ;
th is.  prop2 =  prop2; 
this prop3 = prop3;

}

2- call it using anew keyword


*Arrays and objects can be used to create complex data sets (and both can contain the other).*


* THIS (IT IS A KEYWORD)

The keyword this is commonly used inside functions and objects.
Where the function is declared alters what this means. It always refers
to one object, usually the object in which the function operates.

* RECAP: STORING DATA

If you want to access items via a property name or key, use an object
(but note that each key in the object must be unique).
If the order of the items is important, use an array.


* WHAT ARE BUILT-IN OBJECTS?

built-in objects act like a toolkit for creating interactive web pages.

1- BROWSER OBJECT MODEL
2- DOCUMENT OBJECT MODEL
3- GLOBAL JAVASCRIPT OBJECTS


**THE BROWSER OBJECT MODEL: THE WINDOW OBJECT**

- [x] window . innerHeight-----Height of window (excluding browser chrome/user interface) (in pixels)

- [x] window.innerWidth ------ Width of window (excluding browser chrome/user interface) (in pixels)

- [x] window. pageYOffset ------- Distance document has been scrolled horizontally (in pixels)

- [x] window.screenX  ------ X-coordinate of pointer, relative to top left corner of screen (in pixels)

- [x] window.document ----- Reference to document object, which is used to represent the current page contained in window

- [x] window.screen ------Reference to screen object

- [x] window. a 1ert ()------ Creates dialog box with message (user must click OK button to close it)

- [x] window. open ()----- Opens new browser window with URL specified as parameter 



**THE DOCUMENT OBJECT MODEL: THE DOCUMENT OBJECT**

- PROPERTY
  - document.title------- Title of current document
   - document. l astModified--------Date on which document was last modified
    - document .URL------Returns string containing URL of current document
     - document.domain-------Returns domain of current document

- METHOD
  - document.write()----- Writes text to document
   - document . getElementByld()------- Returns element, if there is an element with the value of the id attribute that matches


**DATA TYPES REVISITED**

1. String
2. Number
3. Boolean
4. Undefined
5. Null
6. 0bject


-  String

|PROPERTY|DESCRIPTION|
|--------|-----------|
|length|Returns number of characters in the string in most cases|
|METHOD|DESCRIPTION|
|------|-----------|
|toUpperCase ()|Changes string to uppercase characters|
|charAt ()|Takes an index number as a parameter, and returns the character found at that position|
|indexOf()|Returns index number of the first time a character or set of characters is found within the string|
|trim()|Removes whitespace from start and end of string|

- NUMBER OBJECT

|METHOD|DESCRIPTION|
|------|-----------|
|i sNaN ()|Checks if the value is not a number|
|toFixed()|Rounds to specified number of decimal places (returns a string)|
|toPrecision()|Rounds to total number of places (returns a string) |
|toExponentia1 ()|Returns a string representing the number in exponential notation|



- MATH OBJECT

PROPERTY|DESCRIPTION|
|--------|-----------|
|Math.PI|Returns pi (approximately 3.14159265359)|
|METHOD|DESCRIPTION|
|------|-----------|
|Math. round()|Rounds number to the nearest integer|
|Math.sqrt (n))|Returns square root of positive number, e.g., Math. sqrt (9) returns 3·|
|Math.cei1 ()|Rounds number up to the nearest integer|
|Math.random()|Generates a random number between 0 (inclusive) and 1 (not inclusive)|


- DATE OBJECT (AND TIME)

|METHOD|DESCRIPTION|
|------|-----------|
|getDay ()|Returns the day of the week (0-6)|
|getDate() setDate()| Returns I sets the day of the month (1-31) |
|getSeconds() setSeconds()| Returns I sets the seconds (0-59))|
|to String() |Returns a string representing the specified date|


















