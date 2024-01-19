# <p align="center">Guide to Minesweeper</p>

### Basic Intro
Minesweeper is  generally a single-player (except here) puzzle video game. The objective of the game is to clear a square board containing hidden "mines" or bombs without detonating any of them, with help from clues about the number of neighbouring mines in each field. You can read the history and more from [Wikipedia](https://en.wikipedia.org/wiki/Minesweeper_(video_game)).

### Modes & Difficulty levels
- Single player - The mines are set randomly. You can win only when you reveal all the cells except those containing mine, else you lose. It has 3 difficulty levels. 
  - BEGINNER - 9x9 Mine field containing 10 mines.
  - INTERMEDIATE - 16x16 Mine field containing 40 mines.
  - ADVANCED - 24x24 Mine field with 99 mines.
- Multiplayer - Player 2 sets the mines manually. This mode supports only 9x9 Mine field containing 10 mines. Player 1 wins only when (s)he reveals all the cells except those containing mine, else player 2 wins.

### Rules
- The board is divided into cells, with some mines distributed in them.
- The number on a cell shows the number of mines adjacent to it.
- Using this information, you can determine cells that are safe, and cells that contain mines.
- You will have some flags (equal to the number of mines), which you can use to mark `F` the cells that might contain a mine.
- The row and column numbers will be mentioned on the left and upper side respectively to help you.
- Input format :
  - `D x y` - Dig the cell located at (x, y), provided the cell is not revealed yet and unflagged.
  - `F x y` - Flag the cell located at (x, y), provided the cell is not revealed yet.
  - `U x y` - Unflag the cell located at (x, y), provided the cell is flagged.
- The first cell revealed is always safe.
- For achieving this in multiplayer mode, player 2 needs to give 1 extra input, so that it can be used to replace the mine from the first dug cell to it (provided the first dug cell contains a mine) to make it safe.
- Input format is always mentioned in the game. Wrong input format may lead to termination of the game.


### Gameplay Screenshots
- **Single player mode**
- `Welcome Message and Help Guide` <br>
![Screenshot from 2024-01-19 17-09-04](https://github.com/DeshDeepakKant/minesweeper/assets/118960904/69db1f56-4a5c-46b1-9584-85e471554698)


![Screenshot from 2024-01-19 17-09-20](https://github.com/DeshDeepakKant/minesweeper/assets/118960904/d4d6260b-ae7b-4750-81db-076d858b40fa)


![Screenshot from 2024-01-19 17-09-30](https://github.com/DeshDeepakKant/minesweeper/assets/118960904/bc8b1fb0-04dc-4439-830b-de02c141ee54)


![Screenshot from 2024-01-19 17-09-45](https://github.com/DeshDeepakKant/minesweeper/assets/118960904/22eb4e3b-0b62-4a9a-8b2c-9766181cdb9b)


![Screenshot from 2024-01-19 17-09-56](https://github.com/DeshDeepakKant/minesweeper/assets/118960904/60dfc49a-353b-4584-a8f4-f6ef1834e78e)








