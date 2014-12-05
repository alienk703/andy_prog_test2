 For this exercise, you need to develop a simple grid framework for a project from scratch.

The grid needs to be a basic 960px grid, with the content centered and a 20px gutter inbetween. Each column block should be 100px in height, and should match the colors from the given example pics. (col-third: red, col-fourth: yellow, col-half: blue). You shouldn't need to edit the html, but if you do, please specify that you did. 

For screens 960px wide and above, the grid should adhere to the greaterThan960px example, the columns should have the specified width;
For screens less than 960px, the columns should stack and take up 100% of the width, with 20px margins on the sides. 


Specs

>= 960px
width - 960px, content centered.
gutters of 20px, just like the picture
.col-third - take up a third of the grid, background color of red
.col-fourth - take up a fourth of the grid, background color of yellow
.col-half - take up half of the grid, background color of blue
all columns take up 100px in height

< 960px
width - 100%
gutters 20px, just like picture
all columns take up the whole width
all columns take up 100px in height


Notes

We are grading you on your ability to write the code that matches the example pictures perfectly. We value clean and semantic code, in the sense that anyone who is given this code can understand what is going on quickly and easily.

Included in this exercise is the bourbon library, feel free to use any of the mixins included with it. http://bourbon.io/docs/

All of the classes you need to build the grid framework are in the sass file, ie you should only need to edit the container and col classes, but if more classes are needed, please specify that you did so.  

Please include the the scss and css file when you send your answers to us.
