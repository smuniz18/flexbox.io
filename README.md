# flexbox.io

<!--
What is a Flexvbox?

The CSS3 Flexible Box, or flexbox is a layout mode intended to accommodate different screen sizes and different display devices. The display order of flexbox elements is independent of their order in the source code. Popular layouts can thus be achieved more simply and with cleaner code.

Definition of display css:
flex = the entire width of the screen
inline-flex = just the width of your content

Flex direction
Flex directions is based on the main axis. This will be the basis for the direction that all flexbox items travel in.

Flex-direction: row; (Boxes in a row)
-Main axis from left to right
Flex-direction: column; (Stacks the boxes)
-Main axis from top to bottom

We can reverse all of this by using reverse
Flex-direction: row-reverse; 
-Flex direction goes from right to left;
Flex-direction: column-reverse;
-Flex direction goes from bottom to top in reverse

Flex-wrap: wrap

When we would use is?
-With this your CSS will try to responsivly adjust to allow for all of the boxes to show. As you stretch the windown more your items will expand till the reach your specific size.

So what does flex-wrap do?
-It will chop you boxes off to make them fit in the specific width that you had assigned. In doing this you get a resposive design with a box layout that will move at you move your screen!

What is part of the box model and what is not?
-If you try to adjust the margin your code will break, because it is not part of the box model.
-For the box model you can adjust the padding and border!