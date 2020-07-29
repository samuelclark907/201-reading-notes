# Reading Notes 4

## Links
- Links are created using the `<a>` element. Users can click on anything between the opening `<a>` tag and the closing `</a>` tag. You specify which page you want to link to using the href attribute.

- Heres an example: `<a href="http://www.imdb.com">IMDB</a>`.

### Linking to other page on the same site.

- When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.

- If all the pages of the site are in the same folder, then the value of the href attribute is just the name of the file.

### Realtive URLS

- Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.

- To link to a file in the same folder, just use the file name. `<a href="reviews.html">Reviews</a>`

- For a child folder, use the name of the child folder, followed by a forward slash, then the file name. 
`<a href="music/listings.html">Listings</a>`

- You can create links to open email programs with an email address in the "to" field.

- You can use the id attribute to target elements within a page that can be linked to.

## Layout

### Key Concepts

- CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

### Containing Elements

- If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

- A box may be nested inside several other block-level elements. 

### Controlling the Position of Elements

- Normal Flow: Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. 

- Relative Positioning: This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.

- Absolute Positioning: This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements.

- The `float` property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

- Pages can be fixed width or liquid (stretchy) layouts.

- Grids help create professional and flexible designs.

- You can include multiple CSS files in one page.

## Functions, Methods, Objects

### Functions

- Functions consist of a In Chapter 1 you saw that The browser comes with series of statements programmers use objects a set of objects that act that have been grouped to create models of the like a toolkit for creating together because they world using data, and that interactive web pages. perform a specific task. 

- Variable Scope: The location where you declare a variable will affect where it can be used
within your code. If you declare it within a function, it can only be used within that function. 

### Method

- A Method is the same as a function. Except methods are created inside an object.

