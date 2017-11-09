# flexbox.io


1. What is a Flexbox?

The CSS3 Flexible Box, or flexbox is a layout mode intended to accommodate different screen sizes and different display devices. The display order of flexbox elements is independent of their order in the source code. Popular layouts can thus be achieved more simply and with cleaner code.

Definition of display css:
flex = the entire width of the screen
inline-flex = just the width of your content

2. Flex direction
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

3. Flex-wrap: wrap

When we would use is?
-With this your CSS will try to responsivly adjust to allow for all of the boxes to show. As you stretch the windown more your items will expand till the reach your specific size.

So what does flex-wrap do?
-It will chop you boxes off to make them fit in the specific width that you had assigned. In doing this you get a resposive design with a box layout that will move at you move your screen!

What is part of the box model and what is not?
-If you try to adjust the margin your code will break, because it is not part of the box model.
-For the box model you can adjust the padding and border!

4. Flexbox Ordering
To create an orders list with a specific level of spacing you can use the following code

.box {
    flex:1;
}
This will space all of your boxes out equally on the screen

The order property can be called by simply using order

.box3 {
    order:5;
}

This takes the box that we are currently selcting and moving that specific number to the end. Based on how many you move and what number you select you will move it in a specific order.

1 is the default with 2 being the first-last box, then 3, 4, etc...

If you use a negative number (-3) it will do the opposite putting it in front in reverse order.


5. Flexbox Alignment (justify-content)

Justified-content is defined as how the content is aligned on the main axis. In this case the main axis is from left-to-right.

flex-start is the default or align to the left
flex-end is an option to aline to the right side
center would center the content in the middle
space-between seperates the boxes equally to fill the entire width of the display
space-around divides all content as well as the spacing to the right and the left

*This also works if you change the flex-direction to column. (Due to spill over you may need to set the min-height: 100vh)
-It will divide up the boxes the same way it does horizontaly


6. Alignment and Centering (align-items)

Instead on concentrating on the main axis, we are focused on the cross access.

We have the same selectors as in the justify-content section. We can center, flex-start, flex-end, and baseline.

baseline - this will make sure that the bottom of any number or letters matches the bottom of other number or letters.

7. Alignment and Centering (align-content)


