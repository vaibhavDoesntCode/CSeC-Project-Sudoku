# LS-2024 CSeC
## The Project
### Part 1: Sudoku Solver

This project is designed to solve Sudoku puzzles presented by a binary executable. The objective is to create a Python script that interacts with the executable and solves all 420 provided Sudoku puzzles.

## Getting Started

### Prerequisites
- Python 3.x

### Setup
1. Clone this repository to your local machine using:
   ~~~
   git clone https://github.com/vaibhavDoesntCode/CSeC-Project-Sudoku.git
   ~~~
   
2. Ensure the `sudoku` executable is in the project directory and is marked as executable. If not, run the following command:
   ```bash
   chmod +x sudoku
### Running the Sudoku Solver
To solve the Sudoku puzzles, execute the script.py as follows:
~~~python
python script.py
~~~
OR
~~~python
python3 script.py
~~~
The script.py will run the sudoku executable, capture the puzzles, solve them and print the flag 
### Solution Approach
The solver script uses a backtracking algorithm to solve each Sudoku puzzle. The steps involved are:

1. Capture the puzzle from the sudoku executable.
2. Apply the backtracking algorithm to find the solution.
3. Print the solution in the required format.
   
