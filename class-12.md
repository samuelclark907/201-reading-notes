# Animated Charts with Canvas

## The `<canvas>` Element and Basic Usage

- The `<canvas>` element only comes with two attributes width and height which are both optional.

- The defaut width and height will initially be 300 pixels wide and 150 pixels high.

- Ex. `<canvas id="tutorial" width="300" height="150"></canvas>`

## Rendering Context

- The `<canvas>` element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown.

- The `<canvas>` element has a method called `getContext()`, used to obtain the rendering context and its drawing functions.

- `getContext()` takes one perameter which is the type of context.

## Drawing Shapes With Canvas

### The Grid

- The grid or coordinate space refers to the x,y units used. 1 unit equals 1 px.

- But instead of starting from the bottom left this starts at the top left. So the top left starts with x = 0 and y = 0. Everything is going to be relative to that point.

<img src = "https://mdn.mozillademos.org/files/224/Canvas_default_grid.png">

### Drawign Rectangles

- Canvas only supports two shapes rectangle and paths.

- Path - is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. 

### Drawing Paths

- `beginPath()` - Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.

- `Path methods` - Methods to set different paths for objects.

- `closePath()` - Adds a straight line to the path, going to the start of the current sub-path.

- `stroke()` - Draws the shape by stroking its outline.

- `fill()` -  Draws a solid shape by filling the path's content area.

- `moveTo(x, y)` - Moves the pen to the coordinates specified by x and y.

- For drawing arcs or circles we use the `arc()` or `arcTo()` methods

`arc()` takes these perameter `arc(x, y, radius, startAngle, endAngle, anticlockwise)`

- `arcTo()` takes these perameter `arcTo(x1, y1, x2, y2, radius)`

## Applying Styles an Colors

### Colors

- If wre trying toapply colors to a shape there are two important properties we can use: `fillStyle` and `strokeStyle`.

- `fillStyle = color` - Sets the style used when filling shapes.

- `strokeStyle = color` - Sets the style for shape outlines.

### Line Styles

- `lineWidth = value` - Sets the width of lines drawn in the future.

- `lineCap = type` - Sets the appearance of the ends of lines.

- `lineJoin = type` - Sets the appearance of the "corners" where lines meet.

 -`miterLimit = value` - Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.

- `getLineDash()` - Returns the current line dash pattern array containing an even number of non-negative numbers.

- `setLineDash(segments)` - Sets the current line dash pattern.

lineDashOffset = value - Specifies where to start a dash array on a line.

## Drawing Texts

- The canvas rendering context provides two methods to render text.

- `fillText(text, x, y [, maxWidth])` -  Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

- `strokeText(text, x, y [, maxWidth])` - Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

`measureText()` -  Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.

 - 