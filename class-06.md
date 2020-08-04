# Reading Notes 6

## Object

- Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names. 

- In an object variables become known as properties.

- In an object functions become known as methods.

- Literal notation is the easiest and most popular to create an object.

## Document Object Model

- The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. 

- When the browser loads a web page, it creates a model of the page in memory. 

- The DOM specifies the way in which the browser should structure this model using
a DOM tree.

- You will hear people call the DOM an Application Programming Interface (API).

- APls let programs and scripts talk to each other.

## DOM Tree

- As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes. 

- Example 

### The Document Node

### Element Nodes

### Attribute Nodes

### Text Nodes

## Working with the DOM Tree

- Accessing and updating the DOM tree involves two steps.

1. Locate the node that represents the element you want to work with. 

2. Use its text content, child elements, and attributes. 

- DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes. 

## Selecting an Element from a Nodelist

- There are two ways to select an element from a Nodelist

- The item() method and array syntax.

- Both require the index number of the element you want. 

## Selecting Elements Using Class Attributes

- The getElementsByClassName() method allows you to select elements whose class attribute contains a specific value. 

## Selectin Elemenst by Tag Name

- The getElementsByTagName ()method allows you to select elements using their tag name. 

## Selecting Elements Using CSS Selector

- querySelector() returns the first element node that matches the CSS-style selector.

- querySelectorAll() returns a Nodelist of all the matches. 

## Accessing and Changing a Text Node

- To work with text in an element, first the element node is accessed and then its text node. 

## Adding Elements Using DOM Manipulation

1. You start by creating a new element node using the createElement() method. This element node is stored in a variable.

2. createTextNode() creates a new text node. Again, the node is stored in a variable. It can be added to the element node using the appendChi l d () method. 

3. Now that you have your element (optionally with some content in a text node), you can add it to the DOM tree using the appendChi 1 d () method. 

- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery). 

- Browsers offer tools for viewing the DOM tree . 