# Sudoku-Game-cum-Solver ๐งฉ
## Index Of Files Included (A-Z) ๐งพ
### AddRecord.py โ
Performs 2 functions. 
1. Add game details to the database (when requested/on button click).
2. To show the details saved in the database.
### DT.py ๐โ
Provides the Date and Time when the game details requested to be saved.
### EmptySudoku.py 0๏ธโฃ
Contains an empty sudoku puzzle with entry in each cell being '0' (meaning empty).
### SaveSudoku.py ๐พ
Upon requesting, this file tells whether the Game is completed. 
### solver.py โ
As the name suggests, the file solves the puzzle. Suitability of a number in a cell also checked.
### Sudoku.py ๐งฉ
Driver File. GUI designed inside it. Contains various functions (can be understood by following the comments in the source code).

## How to Play โโ
1. Run โถ the "Sudoku.py" file (source code). A window with empty Sudoku board will be shown.
2. To Play a game.
๐ Fill the numbers to set a game.
๐ Click on "Play" button.
๐ Now, start playing (solving) the game. When done, click on "Check" Button.
3. To Solve the game/puzzle.
๐ If stuck & want the solution, click on "Solve" Button.
4. To Save game details.
๐ Click on "Save Record" Button.
5. To peek on the games played so far.
๐ Click on "History" Button.
6. To Clear the values filled in.
๐ Click on "Clear" Button.

## Caution โ 
1. โ  Mandatory to click on "Play" after setting the values. Otherwise, "Check" won't work.
2. โ  Unsolvable Sudoku Puzzles not supported till date (Searching for solution to this).
3. โ  On clicking "Solve", values filled in the board till that time will be considered.
4. โ  Code Specific: For connection to MySQL database, remember to use "username" and "password" as per your system.
5. โ  All the files should be in a single directory. Otherwise, You've to make changes to the import statements.
6. โ  Remember to install MySQL database & the MySQL Python connector.
7. โ  Unsolvable puzzles puts the GUI into a long recursive loop. It may look like the GUI Window has been freezed (which is not).

## References ๐
1. https://www.youtube.com/watch?v=xAXmfZmC2SI&t=0s
2. https://www.youtube.com/watch?v=OF0H0B0IuFM
## Being updated ๐ฌ
