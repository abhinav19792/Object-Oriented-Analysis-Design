### Homework 1 - Question 4
#### 4. Write a simple OO program that implements the Shape example discussed in Lecture 2 on slide 6 but using an OO design rather than the presented functional decomposition solution. Your program should simply print out (to the console) the number of shapes in the “database” and then ask each shape to “display itself” which will also cause a line of output to be generated to the console, one for each shape. The word “database” is in quotes in the previous sentence because you should not actually use a database to write this program. It is perfectly acceptable for your main program to create a collection of shapes before moving on to sorting that collection and displaying the shapes. Your program should support circles, triangles, and squares but should use polymorphism so that the main program doesn't know the type of shape it is dealing with, but instead treats shapes uniformly (similar to the example program in Lecture 2 that involved different types of students). You may use any OO language that you'd like to write this program, just be aware that the grader may have to meet with you if you use a language that they don’t have access to.

#### Team : Abhinav Gupta, Divya Athoopallil, Sravanth Yajamanam, Sowmya Ramakrishnan

##### Solution :

We have implemented the Shape example using an Object-Oriented design. Java has been used as the programming language, and the MainClassMod.java consists of working code.

"Shape" is the superclass which has an attribute and method for the number of edges as well as a method to display shape. This class is inherited by three classes - Circle, Square and Triangle which override the methods in the superclass with their own data. 

Another class MainClassMod has a function sort() which takes the edges of the shape objects, sorts them and returns the sorted objects. 

In main(), we use the random function to randomly generate nine shapes (objects), after which they are printed out, first before sorting and then after sorting. In each case, the getvalue() and displayShape() methods in the superclass are overridden by the particular methods in each of the individual sub-classes.

The screenshot showing the output of the program is as follows:

![Output](https://github.com/sowmya2910/Object-Oriented-Analysis-Design/blob/master/Homework_1/HW1%20Q4%20Output.jpeg)
