# Tic-Tac-Toe

Tic Tac Toe game using Data Structures and Algorithms (DSA), we can break down the game into its components and explain how different data structures and algorithms can be employed to implement it effectively.

Here is a brief overview of how data structures can be used in Tic Tac Toe:

1.	Arrays

•	Topic: Multi-dimensional Arrays <br>
•	Usage: The game board is represented using a 2D array (matrix) : This is a fundamental data structure for representing grid-based games.


2.	Enumeration

•	Topic: Enumerated Types <br>
•	Usage: The Player enum is used to represent cell states : While not a complex data structure, enums are useful for representing a fixed set of constants.


3.	Matrix Traversal

•	Topic: Array Iteration <br>
•	Usage: Used in multiple methods, such as initializeBoard() and isBoardFull() : This demonstrates nested loop traversal of 2D arrays.


4.	Linear Search

•	Topic: Searching Algorithms <br>
•	Usage: Implemented in isBoardFull() method : This is a simple linear search to find an empty cell.


5.	State Space Search

•	Topic: Game Tree Algorithms <br>
•	Usage: While not explicitly implemented as a tree, the game logic in play() method explores the game state space : This is a simplified version of state space search used in game playing algorithms.


6.	Boundary Checking

•	Topic: Array Bounds Checking <br>
•	Usage: Implemented in isValidMove() method : This ensures array accesses are within bounds, a crucial concept in array manipulation.


7.	Pattern Matching

•	Topic: String Matching (conceptually similar) <br>
•	Usage: Implemented in checkWin() method : While not string matching, this is conceptually similar to finding a pattern (three in a row).


8.	Game State Representation

•	Topic: State Representation in Game Theory <br>
•	Usage: The entire board state and current player are represented : This demonstrates how to represent the state of a game, a key concept in game programming.


9.	Greedy Method (conceptually)

•	Topic: Greedy Algorithms <br>
•	Usage: The player makes the best move available at each turn, without looking ahead : While not a complex greedy algorithm, this approach of making the immediate best move is conceptually similar to greedy methods.


10.	Loop Invariants

•	Topic: Algorithm Correctness <br>
•	Usage: The game loop maintains invariants, such as the game not being over : This demonstrates the concept of loop invariants in ensuring algorithm correctness.


                                                                                #OUTPUT
![image](https://github.com/user-attachments/assets/269b1ec2-09d6-413a-b8dc-1a6acd7cd1f5)
![image](https://github.com/user-attachments/assets/53c75a98-f4c1-4790-98c1-6b6ccdc6257b)
![image](https://github.com/user-attachments/assets/90f536c2-9f1c-40f0-aba1-fb09ef6d5552)




    
