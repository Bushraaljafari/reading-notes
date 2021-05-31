# Read: 08 - More CSS Layout
## From the Duckett HTML book:

* HTML/CSS book, Ch. 15, “Layout” (again; repeat of Class 4 reading)
- [From the Duckett HTML book:](https://alqudscollege-my.sharepoint.com/:b:/g/personal/advtech_ltuc_com/ETDKUSIt9BxKml92neQqsLoB7WTLFO70vcsmQ8I-HlRTEQ?e=FczW8Q)


### Layout


1. Block-level elements start on a new line Examples include:
\<h1> \<p> \<ul> \<li>

2. Inline elements flow in between surrounding text Examples include:
\<img> \<b> \<i>

* Containing Elements

If one block-level element sits inside another block-level element then the outer box


* Controlling the Position of Elements
1. Normal flow .... position:static
2. Relative Positioning
3. Absolute positioning


* box offset
  - properties to tell the browser how far from the top or bottom and left or right it should be placed
    - 1. Fixed Positioning
       2. Floating Elements



1. *Normal flow .... position:static*

In normal flow, each block-level element sits on top of the next one

2. *Relative Positioning*

Relative positioning moves an element in relation to where it would have been in normal flow

3. *Absolute positioning*

the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.)

4. *Fixed Positioning*

Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed


5. *z-index*

to control which element sits on top


6. *float*

The float property allows youto take an element in normal flow and place it as far to the left or right of the containing element as possible.

7. *clear*

 allows you to say that no element (within the same containing element)

-  left
-  right
-  both
-  none


**Screen Sizes**

* Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

**Screen Resolution**

Resolution refers to the number of dots a screen shows per inch.


**Page Sizes**

- web designers often try to create pages of around 960-1000 pixels wide

**Fixed Width Layouts**

- do not change size as the user increases or decreases the size of their browser window.
- tend to be given in pixels

**Liquid Layouts**

- stretch and contract as the user increases or decreases the size of their browser window
- They tend to use percentages.



**multiple-style-sheets-import**

- @import
- separate style sheets for css 
- ways to add
 1. Your HTML page can link  one style sheet and that stylesheet can use the @import rule to import other style sheets
 2. : In the HTML you can use aseparate \<link> element for each style sheet.