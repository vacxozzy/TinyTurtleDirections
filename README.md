# Unit 8 Project 1 || Tiny Turtle Directions
![Imgur](http://i.imgur.com/Nh1qdMJm.jpg)

Tiny Turtle is a fun Computer Science activity created by a ScriptEd volunteer that teaches students how to use JavaScript functions. The original documentation can be found [here](https://github.com/toolness/tiny-turtle).


#Directions for Set Up
**Step 1: New Repo**      
Create a new GitHub repo called **TinyTurtle**.

<br>
**Step 2: Clone**   
Clone your new repo into a Cloud 9 workspace with a similar name.

<br>
**Step 3: New Files**   
Create three new files in this workspace. Name these new files...

* index.html
* style.css
* script.js

<br>
**Step 4: Linking Files**  
Connect these three files together in the `index.html` file.  
hint: If you need help doing this look at an old project and see how you did it then.

<br>
**Step 5: Import Tiny Turtle**  
Navigate inside the head tag of your HTML page. On the first line inside of the head tag paste the code below:


```
<script src="http://toolness.github.io/tiny-turtle/tiny-turtle.js"> </script>
```  

<br>
**Step 6: Canvas**  
On the first line in the head of the HTML page create a new tag called `canvas`

```
<head>
    <canvas> </canvas>
    <script src="http://toolness.github.io/tiny-turtle/tiny-turtle.js"> </script>
```
The canvas appears on the page but must go in the head. This is an odd feature but it must be completed this way.

<br>
**Step 7: Canvas CSS**  
In the `style.css` page give your canvas tag the following attributes

* a width of 400px
* a height of 400px
* a border (any style)

<br>
**Step 8: JavaScript Set Up**  
In the `script.js` page paste the code below on line 1


```
	TinyTurtle.apply(window); 
``` 

**Step 9: Play Turtle**  
Tiny Turtle understands the following commands:

* forward();
* right();
* left();
* stamp(); <------ This shows which direction the turtle is pointing.  

Use the commands above to make Tiny Turtle travel in a Square.

**Step 10: House**  
For the final piece of this project create a house (square with a triangle ontop)

