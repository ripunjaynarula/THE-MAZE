# THE-MAZE
 MAZE USING EMULATOR 8086

# ABSTRACT

The program is expected to produce a maze structure and the user will then be expected to solve that maze. A maze is a way or assortment of ways, ordinarily from an entry to an objective. The word is utilized to allude both to spreading visit puzzles through which the solver should track down a course, and to less difficult non-fanning ("unicursal") designs that lead unambiguously through a tangled format to an objective. This game is mainly to engage the user and provide the best user experience. The user will be positioned at the starting of the maze called the starting point. The user will be shown many different paths. Some paths will be designed to confuse the user and will lead to dead ends. Only one way among these paths will lead to the final destination. These confusing paths and the ability of the user’s brain to make the right decisions will help the user to activate his brain muscles and will help in exercising them.
The main challenge the user will face is to make the right decisions and reach the end of the maze using a minimum number of moves. This will help the user not only test his ability to make the right decision and exercise his brain but also it could be seen as a fun activity. The number of moves will show how brilliant you are to solve to escape the trap. According to the efficiency of the player, the final score will be generated with respect to the total moves taken. This final score will then be recorded and displayed on the screen for the user to analyze his efficiency to make the right decisions.

# PROPOSED MODEL

![image](https://user-images.githubusercontent.com/66082800/153724464-f2b6f430-b4a7-4f54-88de-22071df570b6.png)

# SOFTWARE REQUIREMENTS

EMU8086 - MICROPROCESSOR EMULATOR primarily emulates the processor, not the other functions that a microcomputer running a 8086 processor would have.

# ALGORITHM

▪ Start the program.

▪ Initialize all variables in the data segment.

▪ Give initial instructions for the player to understand how the game works.

▪ The maze is in the form of a matrix with 0’s and 1’s with 0’s as the final path.

▪ Input the matrix and take the address of each set of elements in a single row and load effective address in the SI.

▪ Write instructions for the player to move using arrow keys.

▪ If the player moves towards a “1” then the player is stationary, else he will move in the desired direction.

▪ Once the end of the maze is reached, we will display a victory image which shows that the player has won.

▪ End the program.

# USER-FLOW

▪ The user will provide input with the help of arrow keys.

▪ The program will then compare the position of the user in the maze and determine whether it's 0/1.

▪ If the position is 0 we will update the position of the player and the score counter will be incremented.

▪ Else if the position is 1 the player will stay at the same place but the score counter will still be incremented.

▪ If the player reaches the exit of the maze the game will be terminated.

