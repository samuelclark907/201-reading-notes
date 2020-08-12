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

### Fixed Width Layout

- To create a fixed width layout, the width of the main boxes on a page will usually be specified in pixels.

- The fixed width layout will stay the same width no matter what size the browser window is, whereas the liquid layout will stretch (or shrink) to fill the screen.

### Liquid Layout

- The liquid layout uses percentages to specify the width of each box so that the design will stretch to fit the size of the screen.

### Layout Grids

- Grids set consistent proportions and spaces between items which helps to create a professional looking design. 

### CSS Frameworks

- Are basically a simple template such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on.

### CSS

- You can include multiple CSS files in one page.