# Illuminati
This repository contains all the code developed to create the game illuminati

# What can we find in this repository?

Here we can find all the files created to rum the game, such as:

## graphics.py

The library is designed to make it very easy for novice programmers to
experiment with computer graphics in an object oriented fashion. It is
written by John Zelle for use with the book "Python Programming: An
Introduction to Computer Science" (Franklin, Beedle & Associates).

LICENSE: This is open-source software released under the terms of the
GPL (http://www.gnu.org/licenses/gpl.html).

## IlluminatiWindow.py

This file contains the class IlluminatiWindow responsible for creating a window so we can have a graphic representation of the board.

## IlluminatiEngine.py

In this file we find the class IlluminatiEngine, which allws us to read a board and save an historic with all the plays made in the baord.

Other functions where added to, for example, eliminate the last board saved in the historic and to help the programm to find a solution in an automatic way.

## IlluminatiShell.py

File with the class IlluminatShell. This class implements all the functions that allow us to make plays in the board and save the board state.

In this files were implemented specific functions:
### do_mr
Command that shows the existing puzzle in a file.

### do_cr
Command that takes a name file as his parameter and loads it to the memory.

### do_gr
Command that allows us to save the board in his current state. 
Takes the name file of the board used as his parameter.

### do_jr
Command that allows the player to select the place where the lamp is placed or from where it is removed.
It uses as his parameters 2 numbers that indicate the row and column where we want to put or remove the lamp.

### do_
