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
**Step 4: index.html**  
Copy and paste the code below into you index.html file

```
<!DOCTYPE html>
<html>
<head>
  
  <title>Tiny Turtle</title>
  <link rel="stylesheet" type="text/css" href="style.css">
  
</head>
<body>
    <h1>Tiny Turtle</h1>
  <canvas></canvas>
  
  <script src="tinyTurtle.js"></script>
  <script src="script.js"></script>
</body>
</html>
```

<br>
**Step 5: Canvas CSS**  
You will notice a new HTML tag is being used. This tag is called `canvas`
In the `style.css` page give your canvas tag the following attributes

* a width of 400px
* a height of 400px
* a border (any style)

<br>
**Step 6: JavaScript Set Up**  
In the `script.js` page paste the code below on line 1


```
	TinyTurtle.apply(window); 
``` 

**Step 7: Play Turtle**  
Tiny Turtle understands the following commands:

* forward();
* right();
* left();
* stamp(); <------ This shows which direction the turtle is pointing.  

Use the commands above to make Tiny Turtle travel in a Square.

**Step 8: House**  
For the final piece of this project create a house (square with a triangle ontop)

