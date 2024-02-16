# FIT1045-Assignment2

In this assignment, you will be using the more advanced concepts you've learned to build a text-based board game inspired by Monopoly named PyPoly.

To win Monopoly, players eliminate opponents by forcing them into bankruptcy. In PyPoly however, the player's goal is to be the first one to purchase a certain target number of properties of the same colour group and build at least one hotel in each of those properties. 

Additionally, players would be able to choose one specific move trait that determines how they move around the game board (i.e. perpendicularly, diagonally or in an L-shape). The PyPoly's game board will be an n x n collection of grids where n is an arbitrary integer.

The rules for PyPoly are:

- At the start of the game, all players will be randomly stationed on the board.
- Every player will start with a fund of $150.
- Players will move to one valid position at each turn (depending on their chosen move trait).
- The grid in the board will be assigned with properties and there will be at least 4 reward 
  or penalty chance assigned grids. 
- If the player lands on a property assigned grid, they can choose to either purchase 
  or pass the property.
- A (non-AI) player should not know what property is contained in a grid that has not been visited yet.
- Each property will be a part of a colour group (either Blue, Green, Red or Yellow).
- If the player lands on a chance assigned grid, they will either face a reduction or 
  addition of funds.
- If a player lands on a property that is previously purchased by another player, the player 
  would have to pay a pass-through rent to the owner. For every hotel built on that property,
  the rent amount will increase by 20%.
- A player may choose to sell one of their properties and relinquish ownership if they choose to.
- The first player who purchases a target number of properties of the same colour group, and 
  builds at least 1 hotel on each property, wins the game. 

In this assignment you'll be creating a command-line version of the above game.

You'll start off by building out each piece individually and merge your solutions into one Python file that can be executed through Command Prompt or Terminal to play.
