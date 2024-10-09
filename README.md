Lab Goal :   This lab was designed to teach you how to use while loops and variables to draw multiple squares and circles

Lab Description :   Write a program that draws shrinking squares and circles.

Part One ::  In the drawSquares method in squares.py, use a loop to draw a series of squares that shrink. The first square is at (0,0) and has a height and width of 100 pixels. Each square is separated by 10 pixels and each following square has a side length that is 10 pixels smaller than the previous square.

The code for drawing a rectangle is below – remember r, g, and b represent the color.

py5.fill(0, 0, b)  # pick a shade of blue
py5.rect(x, y, width, height)

Part One Output : 

![Results](./pyloopsrectcircle/Picture.jpg)




Part Two ::  In the drawCircles method in squares.py, use a loop to draw a series of circles that shrink. The first circle is at (300,300) and has a radius of 100 pixels. To show that there are multiple circles store green as a variable equal to 255 and subtract 25 from it every time the circle shrinks

The code for drawing a circle is below.
py5.fill(0, g, 0) # Shades of green  NOTE: Change g for each circle
py5.ellipse(x, y, width, height)

Part Two Output : 



