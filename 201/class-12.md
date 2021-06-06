# Readings : Chart.js, Canvas
## Reading
-  [article](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/) on the Chart.js API.

- [Chart.js docs](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/): You’ll be needing these!

- Read the following articles on the Canvas API.

1. [Basic usage](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
2. [Drawing shapes with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
3. [Applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
4. [Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)


**EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS**

1. Setting up
 - download Chart.js.
 - create a new html page and import the script


2. Drawing a line chart
 -  create a canvas element in our HTML
 - write a script that will retrieve the context of the canvas

3. Drawing a pie chart
  - need the canvas element
  - need to get the context and to instantiate the chart
  -  need to create the data

4. Drawing a bar chart
 - dd the canvas element
 -  we retrieve the element and create the graph
 - dd in the bar chart’s data

**Basic usage of canvas**

*The \<canvas> element*

- \<canvas id="tutorial" width="150" height="150">\</canvas>
- The id attribute isn't specific to the <canvas> element but is one of the global HTML attributes 
- The \<canvas> element can be styled just like any normal image (margin, border, background…).

*Fallback content*

- Providing fallback content is very straightforward: just insert the alternate content inside the \<canvas> element

- 1.  Browsers that don't support \<canvas> will ignore the container and render the fallback content inside it.
  
  2. Browsers that do support \<canvas> will ignore the content inside the container, and just render the canvas normally.

*Required \</canvas> tag*

- If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.

*The rendering context*

- The \<canvas> element creates a fixed-size drawing surface that exposes one or more rendering contexts

*Checking for support*

- Scripts can also check for support programmatically by testing for the presence of the getContext() method



**Drawing shapes with canvas**

- Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high


- *Drawing rectangles*

1. Draws a filled rectangle

 fillRect(x, y, width, height)

2. Draws a rectangular outline.

strokeRect(x, y, width, height)

3. Clears the specified rectangular area, making it fully transparent.

clearRect(x, y, width, height)

- *Drawing paths*

1. First, you create the path.
2. Then you use drawing commands to draw into the path.
3. Once the path has been created, you can stroke or fill the path to render it.




- beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
- Path methods
Methods to set different paths for objects.
- closePath()
Adds a straight line to the path, going to the start of the current sub-path.
- stroke()
Draws the shape by stroking its outline.
- fill()
Draws a solid shape by filling the path's content area.

- *Moving the pen*

- moveTo(x, y)

Moves the pen to the coordinates specified by x and y.

- lineTo(x, y)

Draws a line from the current drawing position to the position specified by x and y.

- To draw arcs or circles, we use the arc() or arcTo() methods.

- quadraticCurveTo(cp1x, cp1y, x, y)

Draws a quadratic Bézier curve from the current pen position to the end point specified by x and y, using the control point specified by cp1x and cp1y.

- bezierCurveTo(cp1x, cp1y, cp2x, cp2y, x, y)

Draws a cubic Bézier curve from the current pen position to the end point specified by x and y, using the control points specified by (cp1x, cp1y) and (cp2x, cp2y).

- rect(x, y, width, height)

Draws a rectangle whose top-left corner is specified by (x, y) with the specified width and height.


- Path2D()

The Path2D() constructor returns a newly instantiated Path2D object, optionally with another path as an argument (creates a copy), or optionally with a string consisting of SVG path data.

- Path2D.addPath(path [, transform])

Adds a path to the current path with an optional transformation matrix.

**Applying styles and colors**

*Colors*

- fillStyle = color

Sets the style used when filling shapes.

- strokeStyle = color

Sets the style for shapes' outlines.

*Transparency* 

- globalAlpha = transparencyValue
- example :ctx.strokeStyle = 'rgba(255, 0, 0, 0.5)';

*Line styles*

- lineWidth = value

Sets the width of lines drawn in the future.

- lineCap = type

Sets the appearance of the ends of lines.

- lineJoin = type

Sets the appearance of the "corners" where lines meet.

- miterLimit = value

Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.

- getLineDash()

Returns the current line dash pattern array containing an even number of non-negative numbers.

- setLineDash(segments)

Sets the current line dash pattern.

- lineDashOffset = value

Specifies where to start a dash array on a line.



*Gradients*

- createLinearGradient(x1, y1, x2, y2)

Creates a linear gradient object with a starting point of (x1, y1) and an end 
point of (x2, y2).

- createRadialGradient(x1, y1, r1, x2, y2, r2)

Creates a radial gradient. The parameters represent two circles, one with its center at (x1, y1) and a radius of r1, and the other with its center at (x2, y2) with a radius of r2.

- createConicGradient(angle, x, y)

Creates a conic gradient object with a starting angle of angle in radians, at the position (x, y).

- gradient.addColorStop(position, color)

Creates a new color stop on the gradient object


*Patterns*

- createPattern(image, type)

Creates and returns a new canvas pattern object.


1. repeat

Tiles the image in both vertical and horizontal directions.

2. repeat-x

Tiles the image horizontally but not vertically.

3. repeat-y

Tiles the image vertically but not horizontally.

4. no-repeat

Doesn't tile the image. It's used only once.


*Shadows*

- shadowOffsetX = float

Indicates the horizontal distance the shadow should extend from the object. This value isn't affected by the transformation matrix. The default is 0.

- shadowOffsetY = float

Indicates the vertical distance the shadow should extend from the object. This value isn't affected by the transformation matrix. The default is 0.

- shadowBlur = float

Indicates the size of the blurring effect; this value doesn't correspond to a number of pixels and is not affected by the current transformation matrix. The default value is 0.

- shadowColor = color

A standard CSS color value indicating the color of the shadow effect; by default, it is fully-transparent black.

**Drawing text**

- fillText(text, x, y [, maxWidth])

Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

- strokeText(text, x, y [, maxWidth])

Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

**Styling text**

- font = value

The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif. 

- textAlign = value

Text alignment setting. Possible values: start, end, left, right or center. The default value is start.

- textBaseline = value

Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic. 

- direction = value

Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.


**Advanced text measurements**

- measureText()

Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.

