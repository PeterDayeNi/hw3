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

What's the point of the h variable?

What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?

What's the point of an object?

What's an example of a range you might use for the map function?

What line of code would give me a random year in the last century?
