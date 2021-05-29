# Read: 06 - JS Object Literals; The DOM
## Understanding The Problem Domain Is The Hardest Part Of Programming

**What is the hardest thing about writing code?**

- Learning a new technology
- Naming things
- Testing your code
- Debugging
- Fixing bugs
- Making software maintainable


*By creating a familiar problem domain, I found that both the tasks of me teaching a new technology and the viewer learning that technology were much easier, because it is very difficult to learn more than one thing at once*


* Why problem domains are hard

 one are so hard, is because you can’t really see what you are trying to build very clearly


* Programming is easy if you understand the problem domain

*It is very difficult to solve a problem before you know the question.  It’s like buzzing in on Jeopardy before you hear the clue and shouting out random questions.*

* What can you do about it?
1- Make the problem domain easier
2- Get better at understanding the problem domain


*Quick update on my new product*
So many developers don’t realize**how much of an impact marketing themselves and branding can have on their opportunities**

[link](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)


## From the Duckett JS book

* Chapter 3: “Object Literals” (pp.100-105)
* Chapter 5: “Document Object Model” (pp.183-242



**WHAT IS AN OBJECT?**
*Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.*

* IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES
* IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS

* example

var hotel = {

name : 'Quay',

age : 50,

gym: true,

rome;['twin','suit'],

checkAvailability: function() {
return this.rooms - this.booked;}

};


**Document Object Model**

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

*THE DOM TREE IS A MODEL OF A WEB PAGE*

As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes.


* Accessing and updating the DOM tree involves two steps:
1: Locate the node that represents the element you want to work with.
2: Use its text content, child elements, and attributes.

*DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.*

*When a DOM method can return more than one element, it returns a Nodelist (even if it only finds one matching element).*


* SELECTI NG ELEMENTS USING CLASS ATTRIBUTES

The get El ementsByCl ass Name()method allows you to select elements whose c 1 ass attributecontains a specific value. 

* SELECTING ELEMENTS BY TAG NAME

The get El ementsByTagName () method allows you to select elements using their tag name.

* SELECTING ELEMENTS USING CSS SELECTORS

* LOOPING THROUGH A NODELIST

It involves finding out how many items are in the Nodelist, and then setting a counter to loop through them, one-by-one.

* TRAVERSING THE DOM

When you have an element node, you can select another element in relation to it using these five properties.

* ADDING ELEMENTS USING DOM MANIPULATION
  - CREATE THE ELEMENT 'createElement()'
   - GIVE IT CONTENT 'createTextNode()'
    - ADD IT TO THE DOM 'appendChild()'

* REMOVING ELEMENTS VIA DOM MANIPULATION
  - STORE THE ELEMENT TO BE REMOVED IN A VARIABLE
   - STORE THE PARENT OF THAT ELEMENT IN AVARIABLE
    - REMOVE THE ELEMENT FROM ITS CONTA INING ELEMENT

* COMPARING TECHNIQUES: UPDATING HTML CONTENT

1. document.write()
2. eZement.innerHTML

* CROSS-SITE SCRIPTING (XSS) ATTACKS
  - HOW XSS HAPPENS

  Data you do not have complete control over is known
as untrusted data; it must be handled with care.

  - WHAT CAN THESE ATTACKS DO?

  *XSS can give the attacker access to information in:*
 1. The DOM (including form data)
 2. That website's cookies
 3. Session tokens: information that identifies you
 4. from other users when you log into a site

*XSS: VALIDATION & TEMPLATES*
* FILTER OR VALIDATE INPUT

The most basic defense is to prevent users from entering characters into form fields that they do not need to use when providing that kind of information.

*XSS: ESCAPING & CONTROLLING MARKUP* 

- ESCAPING USER CONTENT
All data from untrusted sources should be escaped on the server before it is shown on the page. Mosserver-side languages offer helper functions that will strip-out or escape malicious code.

- ADDING USER CONTENT


*CHECK FOR AN ATTRIBUTE AND GET ITS VALUES*
- The hasAttri bute()
  - lets you check if an attribute exists.
   - the code inside the curly braces will run only if the attribute exists on the given element.

*CREATING ATTRIBUTES & CHANGING THEIR VALUES*

The setAttri bute() method allows you to update the value of any attribute. It takes two parameters: the attribute name, and the value for the attribute.

*REMOVING ATTRI BUTES*

To remove an attribute from an element
1.  select the element,
2. call removeAtt r i bute () .


* Browsers offer tools for viewing the DOM tree such as

FIREFOX,CHROME


[link Duckett JS book](https://drive.google.com/file/d/1L74jU_Js5jSjbi2hg87TNyT-hnVkoXwJ/view).












