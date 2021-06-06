# Positioning 

## position: static

* Default positioning in CSS 
* Says that elements show follow the flow of the HTML document

## position: relative

* Just like static positiong
* However, you can now move the expect from the top, right or bottom.
*  Moves the selected element wherever you specified from wherever is was originally
* All other elements on the page get ignored.
* In practice, T L R B aren't going to be used with relative positioning because makes it diffcult to style anything it

## position: absolute

* Used with T L R B
* Removes the element from the normal document flow
* Positioned in relation to its containing element if the contain element has a position other then ``position: static``
* Other elements simply ignore the space that elemement would have taken
* Useful when you want to put something in a specific position and not affect anything around it

## position:fixed
* Stays in the same place as you scroll
* Position in relative to the entire ``<html>`` element