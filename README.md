# Tic Tac Toe Game
## Project Overview
This project was modeled after RealPython's tutorial on creating a Tic Tac Toe game using Python's Tkinter library, which can be found in this [link](https://realpython.com/tic-tac-toe-python/) (Pozo Ramos & Real Python, 2022)! This project aims to:
- Implement the Tic-Tac-Toe game using object-oriented programming principles to ensure the code's modularity, reusability, and maintainability.
- Improve proficiency in Python by applying OOP concepts such as classes, objects, inheritance, encapsulation, and polymorphism.
- Design a simple and intuitive user interface to interact with the game via Tkinter, ensuring ease of use and a smooth user experience.
- Perform thorough testing to identify and fix bugs, ensuring the game operates correctly under various scenarios.
- Share the project on GitHub to showcase programming skills and project work to potential employers, peers, and the wider programming community.
  
The game created follows the conventional Tic-Tac-Toe game rules, which can be referred to through this [link](https://www.exploratorium.edu/explore/puzzles/tictactoe) (*Tic Tac Toe | Exploratorium*, 2023). It is currently only playable in the 3 by 3 sized grid with two human players. Improvements to the projects will be made soon, which include introducing a selection of varying sizes (e.g. 4x4, 5x5) and the ability to play against a computer program.
## Game Logic and Algorithm
1. The code initiates as an executable program and instantiates `game` and `board` variables from the `TicTacToeGame` and `TicTacToeBoard` classes, respectively.
2. The board and grid are displayed, and the game algorithm waits for input from the players.
<img src="https://github.com/nlawira/tic-tac-toe/blob/main/Images/start_menu.png" alt="Start Screen" width=45%/>
3. The players take turns clicking the grids where they want to place their X/O marks. After every click, the algorithms register the marked grid's coordinates and label the grid with the respective player's mark.
<p float="left">
  <img src="https://github.com/nlawira/tic-tac-toe/blob/main/Images/x_turn.png" alt="Player X's Turn" width=45%/>
  <img src="https://github.com/nlawira/tic-tac-toe/blob/main/Images/o_turn.png" alt="Player O's Turn" width=45%/>
</p>
4. Afterward, it searches through a list of winning combinations, 3 in a row either horizontally, vertically, or diagonally, and checks whether the current grid fulfills any of them. If it does not, it checks whether the grid is entirely filled. If it is, then the game is tied. Otherwise, the turn passes on to the next player.
<p float="left">
  <img src="https://github.com/nlawira/tic-tac-toe/blob/main/Images/win_screen.png" alt="Win Screen" width=45%/>
  <img src="https://github.com/nlawira/tic-tac-toe/blob/main/Images/tied_game.png" alt="Tied Game" width=45%/>
</p>
5. After the game is over, players can reset or exit it by selecting it from the menu bar at the top right.
<img src="https://github.com/nlawira/tic-tac-toe/blob/main/Images/menu_bar.png" alt="Menu Bar" width=45%/>

## References
1. Pozo Ramos, L. & Real Python. (2022, June 27). *Build a Tic-Tac-Toe game with Python and Tkinter*. Retrieved May 20, 2024, from https://realpython.com/tic-tac-toe-python/
2. *Tic Tac Toe | Exploratorium*. (2023, April 4). Exploratorium. https://www.exploratorium.edu/explore/puzzles/tictactoe
