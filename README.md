# hw3

P&E Homework 2

This repository is for Computational Practice 1 Assignment 2

What code draws the blades of grass?

    stroke(random(60, 70), 100, 90);
    line(x, height-10, x+random(-10, 10), height-10-random(h));
    noStroke();

What code makes the "lawnmower" come by? How often does it come by?

    if (random() > 0.999) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
    
It comes randomly.

What's the point of the h variable?

h variable control how tall the grass is and because it is random so it look more like grass.

What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?

The -10 in the second and fourth arguments make the line always above 390, because it help grass start growing and end above the ground. 

What's the point of an object?

Object is the foundation of the Java. Object is kind of "what you think they are."

What's an example of a range you might use for the map function?

    map(mouseX, 0, 400, 0, 255)

What line of code would give me a random year in the last century?

    random (1900, 1999)
