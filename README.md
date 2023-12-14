Description

"Connect Four," which Milton Bradley first launched in 1974. It is also known as Plot Four and Four-in-a-row. Participants in this traditional two-player game compete on an upright board with six rows and seven vacant holes. Every player starts with the same amount of 21 pieces. The players alternately place these pieces strategically as they are dropped one at a time from the top of the board. Being the first to form a straight line made of four pieces in any direction—vertical, horizontal, or diagonal—is the goal. The game is a perennial classic that is loved by people of all ages due to its combination of strategic complexity and simplicity.It is reported that Captain James Cook and his officers played the centuries-old game of Connect 4 during their long travels. Hasbro now owns the commercial version of the game.

Problem Statement: 
Played on a 6x7 grid, connect 4 is a traditional zero-sum game in which two players alternately place their coloured discs into columns. The goal of the game is to line up four of your own discs in a row before your opponent does, either horizontally, vertically, or diagonally. The goal of the research is to investigate how the minimax algorithm may be used to create an artificial intelligence (AI) agent that can play this game strategically.

Method for Implementing the Game:
Configure the Connect 4 game environment such that it tracks the current game state and allows player movements.
•	Minimax Algorithm: Comprehend and put into practice the minimax algorithm, which looks at the decision tree to find the best course of action for the AI.
•	Integration of AI Players: Give the AI player access to the minimax algorithm so it may decide wisely depending on the situation of the game at that moment.
•	Visualization of Decision Trees: Make graphical depictions of the decision tree to show how the AI assesses potential actions.
•	Iteration and Testing: Test the AI against various circumstances and human players, making necessary adjustments to the algorithm and strategy.

The Connect 4 Game Environment Deliverables
A working Connect 4 gaming world with multiplayer functionality.
•	AI based on minimaxes: An AI player making strategic decisions by applying the minimax algorithm.
•	Visualization of Decision Trees: Decision tree visualizations for certain game states.
•	Report on Performance Evaluation: documentation outlining the capabilities, shortcomings, and performance of the AI.

Technology

Numpy: Python's NumPy library is used for numerical operations. The game board, which is represented as a 2D NumPy array, is created and altered using this code.
Pygame is a collection of Python modules made specifically for creating video games. This code uses Pygame to create the Connect Four game's graphical user interface (GUI), handle user input, and show the game board.

Random: To generate random numbers, use the random module. This code makes random decisions during specific game scenarios and uses randomization to decide which player moves first.
Math: Mathematical operations are performed using the math module. It represents both positive and negative infinity values in the minimax algorithm in this code.

Utilising these libraries and modules, the code implements the game logic, which includes player moves, determining a victory condition, and selecting the AI player's move using the minimax algorithm. This results in a graphical depiction of the Connect Four game.

Requirements
•	Python

Installation
1.	Clone the repository: https://github.com/PavanTejaSripati/AI_Project.git
2.	Run the game: python connect4.py 
