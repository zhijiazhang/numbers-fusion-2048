## Numbers Fusion (2048)

Overview:

A single player number tile game played on a plain 4×4 grid, with numbered tiles that slide when a player moves them using the four arrow keys.

Every turn, a new tile randomly appears in an empty spot on the board with a value of either 2 or 4. Tiles slide as far as possible in the chosen direction until they are stopped by either another tile or the edge of the grid. If two tiles of the same number collide while moving, they will merge into a tile with the total value of the two tiles that collided.The resulting tile cannot merge with another tile again in the same move.

The goal is to merge tiles to create a tile that is worth **2048**

## How it was built
The game's code base is organized by the MVC(Model-View-Controller) design pattern. The model is represented by the `Model`, `Side`, `Board`, and `Tile` classes, which determine the state of the game board. The view is represented by the `GUI`(graphical user interface) class, and the Controller resides in the `Game` class. All components of this game was written in Java 15.

## Game Demo
![Alt Text](https://media.giphy.com/media/VaC1mkPDJLea08Rgbc/giphy.gif)

### 6 hours later...

<img src="https://i.postimg.cc/x845nbv0/W.png" width="450" height="450">


## Installation and Setup Instructions

1. Clone down this repository
2. Open up your favorite IDE (must support Java), navigate to `main`   file and press `run`.
3. Have fun!
