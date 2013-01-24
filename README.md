Frogger
=======

History
-------
Frogger was designed for my CS 2500 course at Northeastern University, Fundamentals of Computer Science 1. It was a project that we worked on for roughly two months. I began this project with no prior experience in coding in any functional or object-oriented language. The language we used for the project is called Racket, which is derived from the functional programming language Scheme. More information can be found [here](http://racket-lang.org/). 

I began working on this project with a partner, and together we completed the code base. I worked primarily on the code while my partner (a graphic design major) focused on the graphics and assisted with the code when she could. I went beyond the requirements that were specified in class and decided to implement some extra featuers, such as high score tracking and a life counter. This was my first big project that I ever worked on and the first time I ever really delved into creating software.

What's included
---------------
* Racket source code
* Compiled code as a .exe file
* Readme

How it works
------------
As a functional language and a derivative of Scheme, Racket provides support for lists, functions, and basic structures. I use two libraries provided by the university, `htdp/image` and `htdp/universe`. The first one is used for graphical rendering, while the latter is used for execution of the "world" state. The code is divided into sectiosn based on the objects it works upon, whether it be the frog, the cars, or the "swimmers" (logs and turtles). 

I surrounded everything in a "god-world" data structure that encapsulates all data in the game. It contains the current came state (displaying either the main menu, game screen, high scores, or exit screen; represented by an integer), the current game data, and a list of high scores. I also wrote functions to read in input from the keyboard so as to navigate the menu and control the game. 

It is an old file, and by no means perfect, but provides insight as to the way I thought and designed when I was first beginning my career in computer science.
