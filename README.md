# CSP-Sudoku
This repository contains a Python implementation of a Sudoku solver. Sudoku is a popular puzzle game where the goal is to fill a 9x9 grid with digits from 1 to 9 so that each row, column, and 3x3 sub-grid contains all the digits without repetition.

Features
Grid Generation: Create a 9x9 Sudoku grid with random values ranging from 1 to 9. The grid creation process is flexible and not hard-coded, allowing for easy testing and customization.

Validation Functions: Three separate functions are provided to check the validity of rows, columns, and 3x3 sub-grids. These functions return the number of the invalid row, column, or sub-grid.

Solution Function: Implement a solution function that takes an invalid Sudoku grid as input and returns the corrected grid along with the total count of corrected entries.
