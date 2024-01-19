Battleship Game in Python

This Python program implements the classic game of Battleship with a simple command-line interface. The game is played between a user and an AI opponent.

Features:
- User-friendly command-line interface for playing Battleship.
- The game consists of two players: the user and an AI opponent.
- The user and the AI take turns making moves by selecting coordinates to target on the opponent's board.
- The game continues until one player sinks all the opponent's ships.
- Ships are randomly placed on the board at the beginning of the game.

Code Structure:
The code is organized into several classes:
- `Dot`: Represents coordinates on the board.
- `BoardException`: Base exception class for handling board-related exceptions.
- `BoardOutException`: Exception for attempting to shoot outside the board.
- `BoardUsedException`: Exception for attempting to shoot at a previously targeted cell.
- `BoardWrongShipException`: Exception for attempting to add an incorrect ship to the board.
- `Ship`: Represents a ship with methods for checking if it's hit.
- `Board`: Represents the game board with methods for adding ships and making shots.
- `Player`: Base class for both user and AI players.
- `AI`: Represents the AI player with a method for making moves.
- `User`: Represents the user player with a method for inputting moves.
- `Game`: Main class for setting up and running the game.

How to Play:
1. Clone the repository.
2. Run the `battleship.py` script.
3. Follow the on-screen instructions to input your moves and play against the AI.

Feel free to explore and modify the code to enhance the game or integrate it into other projects.
