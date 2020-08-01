# Reading Notes 5

## Images

### Choosing an Image for Your Site.

- Images can be used to set the tone for a site in less time than it takes to read a description.

-  All images are subject to copyright, and you can get in trouble for simply taking photographs from another website.

### Storing Images on Your Site.

- As a website grows, keeping images in a separate folder helps you understand how the site is organized. 

### Adding Images

- To add an image you need to use the `<img>` element. This is an empty element so there is no closing tag.

- Exampe: `<img src="images/quokka.jpg" alt="A family of quokka" title="The quokka is an Australian marsupial."/>`

- You will also often see an `<img>` element use two other attributes that specify its size: height and width.

- Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

## Color

- The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways.

### RGB Values

- These express colors in terms of how much red, green and blue are used to make it up. For example: `rgb(100,100,90)`

### Hex Codes

- These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: `#ee3e80`.

### Color Names

- There are 147 predefined color names that are recognized by browsers. For example: `DarkCyan`.

### Contrast

- It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).

### Other

- CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.

- CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.

## Text

- The properties that allow you to control the appearance of text can be split into two groups.

- Those that directly affect the font and its appearance (including the typeface, whether it is regular, bold or italic, and the size of the text).

- Those that would have the same effect on text no matter what font you were using (including the color of text and the spacing between words and letters).

### Typeface

- This is the font of the content your editing.

- If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.

- You can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center, or justified. It can also be indented.

- You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.