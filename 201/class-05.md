# Read: 05 - HTML Images; CSS Color & Text
## From the Duckett HTML book:

- Chapter 5: “Images” (pp.94-125)
- Chapter 11: “Color” (pp.246-263)
- Chapter 12: “Text” (pp.264-299)


* Adding Images
- \<img>
- \<img src="" alt="" title=" />
 *Height & Width  of Images*
 
 \<img src="" alt="" width="" height="" />

 *Where to Place Images in Your Code*

 1- before a paragraph

 2- inside the start of aparagraph

 3- in the middle of aparagraph

 *Aligning Images Horizontally*

 - \<p>\<img src="" alt="" width=""
height="" align="left" />\</p>

*Aligning Images Vertically*

- top
- middle
-  bottom

\<p>\<img src="" alt="" width=""
 height="100" align="top" />\</p>

*Three Rules for Creating Images*

- Save images in the right format
 - Save images at the right size
  - Use the correct resolution


**Color**
  - You can specify any color in CSS in one of three ways:
    - rgb values
     - hex codes
      - color names

*background-color*

 background-color: rgb(200,200,200);

*opacity, rgba*
*hsl, hsla*

body {
background-color: #C8C8C8;
background-color: hsl(0,0%,78%);}
p {
background-color: #ffffff;
background-color: hsla(0,100%,100%,0.5);}

**text**

* Specifying Typefaces
(font-family)

font-family: Georgia, Times, serif;

* font-size
  - The font-size property enablesyou to specify a size for thefont. 

  - font-size: 1.3em; 

* @font-face

 - allows you to use a font, even if it is not installed on the computer of the person browsing, by allowing you to specify a path to a copy of the font, which will be downloaded if it is not on the user's machine

 * @font-face {
font-family: 'ChunkFiveRegular';
src: url('fonts/chunkfive.eot');}
h1, h2 {
font-family: ChunkFiveRegular, Georgia, serif;}


* text-transform
  - uppercase
   - lowercase
    - capitalize



* text-decoration

credits {
text-decoration: underline;}
a {
text-decoration: none;}

* line-height

In CSS, the line-height
property sets the height of
an entire line of text, so the
difference between the fontsize and the line-height is
equivalent to the leading (as
shown in the diagram above).


* letter-spacing, word-spacing

* text-shadow

text-shadow: 1px 1px 0px #000000;

* :link

This allows you to set styles for links that have not yet been visited.

* :visited 

This allows you to set styles for links that have been clicked on.

* :hover

This is applied when a user hovers over an element with a pointing device such as a mouse


* :active

This is applied when an element is being activated by a user

* :focus

This is applied when an element has focus

a:link {

color: deeppink;

text-decoration: none;}

a:visited {

color: black;}


a:hover {

color: deeppink;

text-decoration: underline;}

a:active {
color: darkcyan;}

**here are the books for the read**

[HTML AND CSS](https://alqudscollege-my.sharepoint.com/:b:/g/personal/advtech_ltuc_com/ETDKUSIt9BxKml92neQqsLoB7WTLFO70vcsmQ8I-HlRTEQ?e=FczW8Q)

[JavaScrip](https://alqudscollege-my.sharepoint.com/:b:/g/personal/advtech_ltuc_com/Ecix8R_amQVPhRpnPyJaSmoBleNloBxgtjgnbXS7T9MgoA?e=PPfTVl).



## Blog Post
[JPEG vs PNG vs GIF](https://blog.imagekit.io/jpeg-vs-png-vs-gif-which-image-format-to-use-and-when-c8913ae3e01d)



**these 3 image formats have significant differences amongst themselves thus making each of them suitable for specific use cases.**


**PNG,JPEG,GIF**

1. TL;DR
   - JPEG --- for all images that contain a natural scene or photograph where variation in colour a intensity is smooth.
    - PNG --- format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos.
     -  GIF ---format for images that contain animations.


2. Compression
   - JPEG --- is a lossy compression specification that takes advantage of human perception.
    - PNG--- is a lossless image format using DEFLATE compression.
     - GIF is also a lossless image format that uses LZW compression algorithm.

3. Transparency
   - JPEG --- images don’t support transparency and are hence not usable for such cases.
    - PNG--- images support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single colour as transparent (index transparency).
      - GIF --- images support transparency by declaring a single colour in the colour palette as transparent (index transparency)


4. Colours
   - JPEG ---images can support around 16 million colours.
    - PNG--- images mainly have two modes — PNG8 and PNG24. PNG8 can support upto 256 colours whereas PNG24 can handle upto 16 million colours like a JPEG image
     - GIF --- images are limited to 256 colours.


5. Animation
Of these 3 formats, only GIF supports animation


**question**
*Where to Place Images in Your Code?*