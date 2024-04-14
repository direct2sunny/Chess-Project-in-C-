
**•	Objective.**


The Chess Game Application aims to provide a playable and functional chess game experience for participants, following all normal rules, including piece movement and special moves like casting. A well-thought-out user interface, complete with check and checkmate signs, makes for intuitive games, while real-time board updates guarantee a smooth experience. With the ability to store movements and results for the last five games, the application will precisely record game history. Restart and new game options offer flexibility and are reinforced by strong error handling. Ensuring maintainability through prioritizing code quality and documentation, as well as validating correctness and stability through extensive testing, guarantees a positive experience for both developers and players.
•	Demonstrate the functionality of the classes.
This C# code snippet is designed for a simple vehicle rental agency system. It outlines the creation and management of a Chess Logic (Moves, Pieces such as Bishop, King, Queen, Knight, Pawn, Rook, Board, Counting, Direction, End of Reason, Game State), and Chess User Interface (Images, Cursors, Game over, Main window). Now, let’s break down the components and functionalities of the program.

**•	Piece Class:**

Piece class represents a position on a chessboard. It encapsulates a row and a column determining square colors, equality comparisons, and moving positions in different directions, which are the coordinates of the position, with properties of Row and Column. It initializes with the new instance of position class.

**1.	Bishop Class:** 

Bishop class encapsulates the behavior and characteristics of a bishop chess piece which moves diagonally across the board., including its movement rules and ability to generate legal moves on a chessboard. 

**2.	King Class:**

King class encapsulates the behavior and characteristics of a king chess piece which can move one square in any direction and is the most crucial piece in the game as its capture leads to the end of the game. including its movement rules, castling capability, and capturing capability in a chess game. 

**3.	Knight Class:**

Knight classs class encapsulates the behavior and characteristics of a knight chess piece which moves in an L-shape: two squares in one direction and one square perpendicular to that direction, including its movement rules and ability to generate legal moves in a chess game. 

**4.	Pawn Class:**

Pawn class encapsulates the behavior and characteristics of a pawn chess piece, including its movement rules, capturing rules, pawn promotion, and special move like en passant capture in a chess game. It has limited movement capabilities but unique capture rules and the potential for promotion.

**5.	Queen Class:**

Queen class encapsulates the behavior and characteristics of a queen chess piece, including its movement rules and ability to generate legal moves in a chess game, which combines the movement capabilities of a rook and a bishop, able to move horizontally, vertically, and diagonally across the board.

**6.	Rook Class:**

Rook class encapsulates the behavior and characteristics of a rook chess piece, including its movement rules and ability to generate legal moves in a chess game. It moves horizontally or vertically across the board.

**•	Player Class:**

A Player class is a blueprint or template that is used to represent a player. It extends functionality pf Player with “Chess Logic”. It includes properties and techniques that specify a player's actions and traits in the context of the game. Player defines three values: None, White and Black which represent players in game.  

**•	Position Class:**

A position class perform’s operations related to positions, such as determining square colors, equality comparisons, and moving positions in different directions in a chessboard. It is represented with Row and Column for storing coordinates of position.

**•	Direction Class:**

A direction class represents directional movements on a grid. In addition to allowing operations between directions like addition and scalar multiplication, it defines numerous static instances representing common cardinal and diagonal directions (north, south, east, west, northeast, northwest, southeast, and southwest). Direction class can be particularly relevant in applications like chess, where pieces move in specific directions.

**•	Piece Type Class:**

Piecetype represents the types of chess pieces that can appear on a chessboard. It provides a straightforward and type-safe way to represent the different types of chess pieces in a chess game implementation and enumerates the various types of pieces: Pawn, Bishop, Knight, Rook, Queen, and King.

**•	Board Class:**

The class manages the state of a chessboard, the placement and movement of chess pieces during a game which has contains all the logic needed to control the position, movement, and special moves of the pieces on a chessboard in addition to identifying game states like check and checkmate.

**•	Game State Class:**

The GameState Class of a chess game, manages the board state, current player, and game result. The logic for managing the progress of a chess game, including legal moves, game state updates, and determining the game result. It also implements rules for detecting draw conditions such as threefold repetition and the fifty-move rule.











