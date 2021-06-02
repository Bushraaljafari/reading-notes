# Readings : Forms and JS Events
##  [From the Duckett HTML book:](https://alqudscollege-my.sharepoint.com/:b:/g/personal/advtech_ltuc_com/ETDKUSIt9BxKml92neQqsLoB7WTLFO70vcsmQ8I-HlRTEQ?e=FczW8Q)


- Chapter 7: “Forms” (p.144-175)
- Chapter 14: “Lists, Tables & Forms” (pp.330-357)


## [From the Duckett JS Book:](https://drive.google.com/file/d/1L74jU_Js5jSjbi2hg87TNyT-hnVkoXwJ/view)


-Chapter 6: “Events” (pp.243-292)

### Forms

**Why Forms?**
The best known form on the web is probably
the search box that sits right in the middle of
Google's homepage

**Form Controls**
*There are several types of form controls that you can use to collect information from visitors to your site.*
- ADDING TEXT
  - Text input (single-line)
   - Password input
    - Text area (multi-line)

- Making Choices:
  - Radio buttons
   - Checkboxes
    - Drop-down boxes


**Information from a form is sent in name/value pairs.**

**Form Structure**

\<form action=""="get">
\<p>This is where the form controls will appear.
 \</p>
\</form

**text-input**

\<form action="">
\<p>Username:
 \<input type="text" name="username" size="15"
maxlength="30" />
\</p>
\</form>


**text area**

\<textarea>

**Radio Button**.

\<input>
- type="radio"
- name
- value
-checked

**checkbox**

\<input>
- type="checkbox"
- name
- value
-checked


**HTML5 introduces new form elements which make it
easier for visitors to fill in forms**

* list-style-type


It can be used on rules that
apply to the \<ol>, \<ul>, and \<li>
elements.
Unordered Lists


* list-style-image

You can specify an image to act
as a bullet point using the
list-style-image property


* list-style-position

Lists are indented into the page
by default and the list-styleposition property indicates
whether the marker should
appear on the inside or the
outside of the box containing the
main points



*table-properties*

- width--- to set the width of the
table
- padding--- to set the space
between the border of each table
- cell---- and its content
text-transform to convert the
content of the table headers to
uppercase
letter-spacing, font-size
to add additional styling to the
content of the table headers
- border-top, border-bottom
to set borders above and below
the table headers
- text-align to align the writing
to the left of some table cells and
to the right of the others
- background-color to change
the background color of the
alternating table rows
- :hover to highlight a table row
when a user's mouse goes over it




* styling-text-inputs
1. font-size sets the size of the
text entered by the user.
2. color sets the text color, and
background-color sets the
background color of the input.
3. border adds a border around
the edge of the input box, and
4. border-radius can be used
to create rounded corners (for
browsers that support this
property).



* styling-submit-buttons

1. color is used to change the
color of the text on the button.
2. text-shadow can give a 3D
look to the text in browsers that
support this property.
3. border-bottom has been used
to make the bottom border of
the button slightly thicker, which
gives it a more 3D feel

*cursor*

- The cursor property allows
you to control the type of mouse
cursor that should be displayed
to users


- Here are the most commonly
used values for this property:
1. auto
2. crosshair
3. default
4. pointer
5. move
6. text
7. wait
8. help
9. url("cursor.gif");




**DIFFERENT EVENT TYPES**

*HOW EVENTS TRIGGER JAVASCRIPT CODE*

1. Select t he element node(s) you want the script to respond to.
2. Indicate which event on the selected node(s) will trigger the response.
3. State the code you want to run when the event occurs.


*TRADITIONAL DOM EVENT HANDLERS*

- element .onevent functionName ;

*EVENT LISTENERS*

- Event listeners are a more recent approach to handling events.
They can deal with more than one function at a time
but they are not supported in older browsers.

- element .addEventlistener('event', functionName [, Boolean]) ;


*SUPPORTING OLDER VERSIONS OF IE*

IES-8 had a different event model and did not support
addEventL i stener() but you can provide fallback code
to make event listeners work with older versions of IE.


if (el .addEventlistener) {
Run the code inside
these curly braces
If it doesn't, do
something else:
Run the code inside
these curly braces

el .addEventlistener('blur', function() {
checkUsername(5);
}, false);
} else {

}
el .attachEvent('onblur', function() {
checkUsername(5);
} )




*THE EVENT OBJECT*

When an event occurs, the event object tells
you information about the event, and the
element it happened upon.


*EVENT DELEGATION*

BENEFITS OF EVENT DELEGATION:
1. WORKS WITH NEW ELEMENTS
2. SOLVES LIM ITATIONSWITH this KEYWORD
3. SIMPLIFIES YOUR CODE


*CHANGING DEFAULT BEHAVIOR*

The event object has methods that change:
the default behavior of an element and how
the element's ancestors respond to the event.

- preventDef au 1t ()
- stopPropagation()
- USING BOTH METHODS


*DIFFERENT TYPES OF EVENTS*

Events are defined in:
• The W3C DOM specification
• The HTMLS specification
• In Browser Object Models



*MOUSE EVENTS*

The mouse events are fired when the mouse is moved and also when its
buttons are clicked.


- You can use event delegation to monitor for events
that happen on all of the children of an element.
- The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events.