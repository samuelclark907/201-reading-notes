# Reading-Notes-09

## Forms

- A form is different elements that allow you to collect information from visitors to your site.

- The best known form is the search box that sits on Google front page.

### Form Controls

#### Adding Text

- `Text input` used for a single line of text such as email addresses and names.

- `Password input` like a single line text box but it masks the characters entered.

- `Text area` for longer areas of text, such as messages and comments.

#### Making Choices

- `Radio buttons` for use when a user must select
one of a number of options.

- `Checkboxes` when a user can select and unselect one or more options.

- `Drop-down boxes` when a user must pick one of a number of options from a list.

#### Submitting Forms

- `Submit buttons` to submit data from your form to another web page.

- `Image buttons` similar to submit buttons but they allow you to use an image.

- `File upload` allows users to upload files (e.g. images) to a website.

### Form Structure

- Form controls live inside a `<form>` element. This element should always carry the actionattribute and will usually have a method and id attribute too.

- Every `<form>` element requires an `action` attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.

- Forms can be sent using one of two methods: `get` or `post`.

- With the `get` method, the values from the form are added to the end of the URL specified in the action attribute.

- With the `post` method the values are sent in what are known as HTTP headers.

## Lists, Tables, and Forms.

### Lists

- List markers can be given different appearances using the list-style-type and list-style image properties.

## Tables

- Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent. 

## Forms

- Forms are easier to use if the form controls are vertically aligned using CSS.

- Forms benefit from styles that make them feel more interactive.

## Events

- When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events. 

- Interactions create events----> Events trigger code----> Code responds to users.

### Different Event Types

- `load` Web page has finished 

- `unload` Web page is unloading (usually because a new page was requested)

- `error` Browser encounters a JavaScript error or an asset doesn't exist

- `resize` Browser window has been resized

- `scroll` User has scrolled up or down the page

#### KEYBOARD EVENTS Occur when a user interacts with the keyboard (see also input event)


- `keydown` User first presses a key (repeats while key is depressed)

- `keyup` User releases a key

- `keypress` Character is being inserted (repeats while key is depressed)

#### MOUSE EVENTS Occur when a user interacts with a mouse. trackpad, or touchscreen


- `click` User presses and releases a button over the same element

- `dbl click` User presses and releases a button twice over the same element

- `moused own` User presses a mouse button while over an element

- `mouseup` User releases a mouse button while over an element

- `mousemove` User moves the mouse (not on a touchscreen)

- `mouseover` User moves the mouse over an element (not on a touchscreen)

- `mouseout` User moves the mouse off an element (not on a touchscreen)

## How Events Triger JS Code

- When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.

1. Select t he element node(s) you want the script to respond to. 

2. Indicate which event on the selected node(s) will trigger the response.

3. State the code you want to run when the event occurs. 

### Event Delegation

- You can use event delegation to monitor for events that happen on all of the children of an element. 