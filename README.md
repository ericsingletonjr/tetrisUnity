# Tetris built in Unity - QDD

This is for learning how to build the classic game Tetris within the Unity IDE. This is to help further solidify the understanding of things such as Prefabs as well as creating a grid that checks whether specific arrays have fully been met

### Mechanics

Main objective of the game is to take a variety of shapes and create seamless rows in order to score and then remove them.

Upon clearing a singular or multiple lines, the remaining blocks will be pushed down to fill in the newly created gap, allowing players to continue with game play.

If the a section of shapes reaches the top of the board, that will result in a game over.


### Shapes

The main objects will be shapes that are similar to alphabetical letters and are groups comprised of blocks. These include:

* L - shaped
* J - shaped
* s - shaped (backwards z)
* z - shaped
* T - shaped
* O - shaped (with blocks it will represent a 4-block square)
* I - shaped

The highest obtainable multi-line clear will be four lines at once.

### Board

The gameplay will take place on a board that is the standard 10x24. This will be related to the size of the blocks that are creating the shapes and set to a tilemap as this will be in the 2D space.

The state of the board will be checked for the following conditions:
* Is a line full
* How many lines cleared at once (up to 4)
* AFTER being placed, does a block exceed the top threshold

