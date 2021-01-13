# SUDOKU_SHREYA_2015282


//Start of readme

Made a Sudoku Game using C++:

//Header files Used header files like iostream cstdio cstring cstdlib

//Declared namespaces: using namespace std;

//Functions Made a function bool SolveSudoku(int grid[N][N]) Assigned values to all unassigned locations for final Sudoku solution

Made a function bool FindUnassignedLocation(int grid[N][N], int &row, int &col) Searched the grid to find an entry that is still unassigned

Made a function bool UsedInRow(int grid[N][N], int row, int num) Returned whether any assigned entry n the specified row matches the given number

Made a function bool UsedInCol(int grid[N][N], int col, int num) Returned whether any assigned entry in the specified column matches the given number

Made a function bool UsedInBox(int grid[N][N], int boxStartRow, int boxStartCol, int num) Returned whether any assigned entry within the specified 3x3 box matches the given number

Made a function bool isSafe(int grid[N][N], int row, int col, int num) Returned whether it will be legal to assign num to the given row,col location

Made a function void printGrid(int grid[N][N]) Printed the final grid

//Start of main Started by taking a grid Checked using solve sudoku And then finally called printGrid to print the final grid //End of main

//End of readme



