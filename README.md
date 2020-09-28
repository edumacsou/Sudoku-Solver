# Sudoku Solver

<details><summary><b> 1. What is this repository?</b></summary></br>

A command-line application that solves sudoku using the brute force method and recursion.

---
</details>

<details><summary><b> 2. What is a sudoku?</b></summary></br>

Sudoku is a Japanese game, based on a table with 81 fields, called cells. These 81 cells are divided into 9 different 3x3 squares, which must be filled with numbers from 1 to 9 following the rule: 
    A number can only appear once on each row, column and 3x3 square.
A perfect sudoku has only one solution, but a sudoku with more solutions can be solved by making a guess.

---
</details>

<details><summary><b> 3. How to run the fractal tree?</b></summary></br>

1. You will need to have Python3 installed, it can be found [here](https://www.python.org/downloads).
2. Download the file "sudoku.py" to a folder of your choice.
3. Open your folder using the terminal with this command (use the path to your folder):
    ```
    cd C:\Users\MyName\Documents\Myfolder\
    ```
4. Run the application with Python3:
    ```
    python sudoku.py
    ```
5. Press "Enter" if you want a new solution.
6. Edit the file "sudoku.py" to put your own sudoku.

---
</details>

<details><summary><b> 4. How to edit and use it?</b></summary></br>

In line 6 there is the definition of the puzzle, saved in the variable grid, in the form of a dimensional array.
The 0 values are blank cells of the puzzle that you want to solve.
You can edit it to insert your own puzzle.
After running the application, it will ask you if you want more solutions. Press the enter key to print another result (if other solutions exist).

---
</details>

<details><summary><b> 5. Concepts used</b></summary></br>

+ Recursion
+ Libraries imports
  + Numpy

---
</details>


