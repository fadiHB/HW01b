JavaScript Loops
Loops are handy, if you want to run the same code over and over again, each time with a different value

nstead of writing:
text += cars[0] + "<br>";
text += cars[1] + "<br>";
text += cars[2] + "<br>";
text += cars[3] + "<br>";
text += cars[4] + "<br>";
text += cars[5] + "<br>";
You can write:
var i;
for (i = 0; i < cars.length; i++) {
  text += cars[i] + "<br>";
}

**Different Kinds of Loops**
JavaScript supports different kinds of loops:

for - loops through a block of code a number of times
for/in - loops through the properties of an object
for/of - loops through the values of an iterable object
while - loops through a block of code while a specified condition is true
do/while - also loops through a block of code while a specified condition is true

**he While Loop**
The while loop and the do/while loop will be explained in the next chapter.