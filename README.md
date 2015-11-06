# Flexbox-examples
Just a bunch of flexbox examples

[View demo](http://joanclaret.github.io/flexbox-examples)

![Screenshot](http://joanclaret.github.io/flexbox-examples/screenshot.jpg)



###  display:flex;   
[flex, inline-flex]

###  flex-direction: row;    
[row, column, row-reverse, column-reverse] 
Changes main and cross axis

###  align-items: center; (cross axis)
[flex-start, flex-end, center, stretch, baseline]
How flex items are laid out along the cross axis 

### justify-content: center; (main axis)
flex-start;     /* Pack flex items from the start */
flex-end;       /* Pack items from the end */
center;         /* Pack items around the center */ 
space-between;  /* The first item at the start, the last at the end */
space-around;   /* Items have equal space around them */
How the browser distributes space between and around flex items along the main-axis of their container

###  flex-basis: <width>;
Specifies the initial size of a flex item

###  flex-grow: <number>;
Defines the ability for a flex item to grow if necessary. It accepts a unitless value that serves as a proportion. It dictates what amount of the available space inside the flex container the item should take up.

###  flex-shrink: <number>;
It specifies the "flex shrink factor", which determines how much the flex item will shrink relative to the rest of the flex items in the flex container when there isn't enough space on the row.

###  flex-wrap: nowrap;
Specifies whether flex items are forced into a single line or can be wrapped onto multiple lines.
[ nowrap, wrap, wrap-reverse ]
