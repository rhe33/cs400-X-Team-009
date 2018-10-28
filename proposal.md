# X-Team 009 UW-Madison Course Enrollment System 

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Improve the user experience using the online class enrollment system.
#1. More accurate results when searching. For example, searching "CS" would return the same results as searching "COMP SCI".
#2. More consistent search results. For example, searching "CS 300" should return a list of computer science courses as on top of the results.
#3. If the searched course is a lower level (closer to the first course in Computer Science), then print the course with that course first and other computer science courses in an ascending order starting from the first course. Example: "Comp Sci 300", "Comp Sci 200", "Comp Sci 252"... 
#4. If the searched course is a higher level course (closer to the last course in Computer Science), then print the course with that course first and other comupter science courses starting from that searched course. Example: "Comp Sci 537", "Comp Sci 540", "Comp Sci 559"...

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

UW-Madison Course Enrollment System

2. Output: Describe the output your program will produce.  Include and example format of the output produced.
A list of classes that are required prerequisites for an intended course enrollment.
A list of classes that use current course enrollments as their required prerequisites.

Enrollment: CS 200
Past Prerequisites: N/A
Classes that use this course as a Prerequisite: CS 300

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
The user will input the course that they want to look up,
or they can input the department of the course.


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
Below is an example of User Interface
![alt text][UI]

[UI]: https://github.com/rhe33/cs400-X-Team-009/blob/master/UserInterface.png "Example User Interface"



5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
We would use a doubly linked list to determine the predecessors and successors of a class.

For example, CS300 has a predecessor of CS200 and a successor of CS400.

We will have a Node class to store the information of each class, like the description, number of credits, and breadth.






Name each interface or class and briefly describe its function or purpose.


Interface: ClassADT
- carry method names to be implemented in Class

Class: Class
- drives the functionality of the program

Nested class: Node
- contains each course as a node with information about it



## Edit and Submit this file and any figures referenced by this document.

