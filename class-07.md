# Reading Notes 7

## Tables

### What's a Table you may ask?

- A table represents information in a grid format. Examples of tables include financial reports, TV
schedules, and sports results.

### Basic table structure

- The `<table>` element is used to create a table. The contents of the table are written out row by row.

- You indicate the start of each row using the opening `<tr>` tag.

- Each cell of a table is represented using a `<td>` element.

- The `<th>` element is used just like the `<td>` element but its purpose is to represent the heading for either a column or a row. 

- The `colspan` attribute can be used on a `<th>` or `<td>` element and indicates how many columns that cell should run across.

- The `rowspan` attribute can be used on a `<th>` or `<td>` element to indicate how many rows a cell should span down the table.

### Long Tables

- The headings of the table should sit inside the `<thead>` element. 

- The body should sit inside the `<tbody>` element. 

- The footer belongs inside the `<tfoot>` element.

## Functions, Methods, Objects

### Updating an Object

- To update properties use dot notation or square brackets.

### THIS

- The keyword `this` is commonly used inside functions and objects. Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates. 

### Other

- Web browsers implement objects that represent both the browser window and the document loaded into the browser window. 

- JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts. 

- Arrays and objects can be used to create complex data sets.