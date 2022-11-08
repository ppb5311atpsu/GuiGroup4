JavaMancalaApp
==============

A Mancala GUI application written in Java.
Mancala (known in the Philippines as "Sunka") is a two player board game that consists of holes and beads. 
The objective of the game is to collect the most beads by clearing the holes at alternating turns.

The implementation of the application is organized using the MVC software design pattern.  Code for the GUI side 
of the application uses Java Swing components written from scratch.  The game logic maintains game states to keep
track of player actions and results.  Player input is accepted through mouse clicks done through the Java panels 
that are diplayed, the game states are updated, then the results update the display back to the user.
