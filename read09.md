## HTML Forms

An HTML form is used to collect user input. The user input is most often sent to a server for processing

## The <form> Element

The HTML <(form> element is used to create an HTML form for user input:

<.form>
.
form elements
.
<./form>

The <.form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

All the different form elements are covered in this chapter: HTML Form Elements.


The <.input> Element
The HTML <.input> element is the most used form element.

An <.input> element can be displayed in many ways, depending on the type attribute.

## The <label> Element

Notice the use of the <.label> element in the example above.

The <.label> tag defines a label for many form elements.

The <.label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

The <.label> element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the <.label> element, it toggles the radio button/checkbox.

The for attribute of the .<.label> tag should be equal to the id attribute of the <.input> element to bind them together.



## HTML Tables

HTML tables allow web developers to arrange data into rows and columns.

## Define an HTML Table

The <.table> tag defines an HTML table.

Each table row is defined with a <.tr> tag. Each table header is defined with a <.th> tag. Each table data/cell is defined with a <.td> tag.

By default, the text in <.th> elements are bold and centered.

By default, the text in <.td> elements are regular and left-aligned.




Tag	Description
<.table>	Defines a table
<.th>	Defines a header cell in a table
<.tr>	Defines a row in a table
<.td>	Defines a cell in a table
<.caption>	Defines a table caption
<.colgroup>	Specifies a group of one or more columns in a table for formatting
<.col>	Specifies column properties for each column within a <.colgroup> element
<.thead>	Groups the header content in a table
<.tbody>	Groups the body content in a table
<.tfoot>	Groups the footer content in a table




|  Tag |Description|    
|---|---|
| <.table>  | Defines a table  |      
| <.th>  |  Defines a header cell in a table |      
| <.tr>	  | Defines a row in a table  | 
| <.td>  | Defines a cell in a table  |      
| <.caption>  | Defines a table caption  |      
| <.colgroup>  | Specifies a group of one or more columns in a table for formatting  |  
| <.col>  | Specifies column properties for each column within a <.colgroup> element  |      
| <.thead>  | Groups the header content in a table  |      
| <.tbody>  |  Groups the body content in a table |  
| <.tfoot>  | Groups the footer content in a table  |   





## JavaScript Events

HTML events are "things" that happen to HTML elements.

When JavaScript is used in HTML pages, JavaScript can "react" on these events.

## HTML Events

An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

An HTML web page has finished loading
An HTML input field was changed
An HTML button was clicked
Often, when events happen, you may want to do something.

JavaScript lets you execute code when events are detected.

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.
       


