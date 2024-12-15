# Sudoku Solver

A command-line Sudoku Solver developed in C that reads Sudoku puzzles from a file, determines their difficulty level, and solves them using a recursive backtracking algorithm. 

## Features
- Reads 9x9 Sudoku puzzles from a text file.
- Determines the difficulty level (Easy, Medium, Hard) based on the number of empty cells.
- Solves puzzles using an efficient backtracking algorithm.
- Displays both the initial puzzle and the solved grid in a user-friendly format.
- Includes error handling for file operations and invalid inputs.

## How It Works
1. The program prompts the user to input the filename containing the Sudoku grid.
2. Reads the grid from the file and calculates the number of empty cells.
3. Determines the puzzle's difficulty level:
   - **Easy**: Less than or equal to 20 empty cells.
   - **Medium**: Between 21 and 40 empty cells.
   - **Hard**: More than 40 empty cells.
4. Solves the puzzle using a backtracking algorithm.
5. Outputs the initial puzzle, its difficulty, and the solved grid.

## Example Input File
The input file should contain a 9x9 grid with numbers separated by spaces, where empty cells are represented as `0`. Example:  

```plaintext
5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
