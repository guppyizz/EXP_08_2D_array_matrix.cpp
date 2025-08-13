# EXP_08_2D_array_matrix.cpp
C++ Matrix Operations
This repository contains two simple C++ programs demonstrating fundamental matrix operations.

Program 1: Matrix Addition
This program calculates the sum of two matrices.

Aim
The goal of this program is to perform the addition of two matrices of the same dimensions. The user is prompted to enter the number of rows and columns for each matrix, and then to input the elements for both. The program calculates the sum and prints the resulting matrix.

Algorithm
Declare variables for rows and columns of both matrices.

Prompt the user to enter the dimensions for the first matrix (m×n) and the second matrix (x×y).

Check if matrix addition is possible. Matrix addition is only valid if both matrices have the same dimensions (i.e., m=x and n=y).

If the dimensions are compatible, declare three 2D arrays: two for the input matrices (mat1, mat2) and one for the result (result).

Use nested loops to iterate through the rows and columns, prompting the user to enter each element of mat1 and mat2.

Perform the addition. Iterate through the rows and columns again, calculating the sum of corresponding elements (mat1[i][j] + mat2[i][j]) and storing the result in the result matrix.

Use another set of nested loops to display the elements of the result matrix to the console.

Program 2: Matrix Input and Display
This program takes a matrix as input and displays it to the console.

Aim
This is a simpler program designed to demonstrate how to take user input for a matrix and then print its contents to the console. It serves as a fundamental example for working with 2D arrays in C++.

Algorithm
Declare variables for the number of rows (m) and columns (n).

Prompt the user to enter the dimensions.

Declare a 2D array (mat) using the user-provided dimensions.

Use nested loops to iterate through each position in the matrix. For each position, prompt the user to enter an element and store it in the array.

After all elements are entered, use another set of nested loops to iterate through the matrix again. This time, print each element followed by a space.

After each inner loop (for a row) completes, print a newline character (\n) to format the output as a matrix.
