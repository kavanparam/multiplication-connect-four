# Multiplication Connect Four
 A two player React app game to further understanding of useState and other important hooks.


### Overview

- 2 player game
- Roll the dice, add the numbers, and multiply by 2

### Goals

Design a 2 player game React app to further understanding of useState, and other React hooks.

### Game Rules

1. Roll two dice.
2. Add the numbers together, and multiply by 2.
3. Select this number within a block in the game.
4. Repeat for the next player.
5. Play until a player connect 4 squares in a row (vertically, horizontally, or diagonally) to win the game.

**e.g.)** `Rolling a 5 and 3, means you can choose any block with the number 16`

### Components

- Two standard dice
    - with roll button to roll both at once
    - output with number to choose on board
- 5x7 Game Board
    - with player selectable blocks
    - blocks containing even numbers ranging from 4-24
    - score tracker showing the most consecutive blocks for a player
- Alternating player selection