# Sudoku Solver Application with pygame GUI

## Overview

This is a Python application for playing and solving Sudoku puzzles using the Pygame library. The application 
provides a graphical interface for users to interact with the Sudoku grid, input numbers, and solve puzzles. 
It also includes functionality to fetch Sudoku boards from an external API and allows users to play or solve them.

## Features

### 1. Sudoku Grid
- The application presents a 9x9 Sudoku grid where users can input numbers.
- The grid is divided into 9 subgrids of 3x3 cells, following the standard rules of Sudoku.

### 2. Input and Sketching
- Users can input numbers from 1 to 9 into empty cells by selecting a cell and pressing the corresponding number key on the keyboard.
- Additionally, users can sketch tentative numbers in cells by holding down the mouse button and dragging over cells while pressing a number key.

### 3. Validation and Error Handling
- The application validates user inputs in real-time according to Sudoku rules.
- Invalid inputs or attempts to place numbers that violate Sudoku constraints are highlighted as errors, and users are notified accordingly.

### 4. Solving
- Users can request the application to solve the Sudoku puzzle by pressing the spacebar.
- The application uses backtracking to solve the puzzle step by step, visualizing the process on the grid.

### 5. Timer and Strikes
- The application features a timer that tracks the time spent by the user to solve the puzzle.
- Users receive strikes for incorrect placements, helping them keep track of mistakes made during the game.

### 6. External Board Fetching
- The application fetches Sudoku boards from an external API, allowing users to play randomly generated puzzles.
- It handles API requests to retrieve new Sudoku boards and integrates them seamlessly into the application.

## How to Use

1. **Launching the Application**:
   - Run the Python script to launch the Sudoku application.
   - The application window will open, displaying the Sudoku grid.

2. **Playing Sudoku**:
   - Click on an empty cell to select it.
   - Press a number key (1-9) to input a number into the selected cell.
   - If you're unsure about a number, you can sketch it by holding down the mouse 
button and dragging while pressing a number key.

3. **Solving Sudoku**:
   - Press the spacebar to let the application solve the puzzle.
   - Watch as the application fills in the grid step by step, visualizing the solving process.

4. **Timer and Strikes**:
   - The timer at the top-left corner of the window tracks the time spent on the puzzle.
   - Strikes are displayed next to the timer, indicating incorrect placements made by the user.

5. **Fetching New Boards**:
   - The application fetches new Sudoku boards from an external API.
   - Users can enjoy playing randomly generated puzzles by simply launching the application.

6. **Exiting the Application**:
   - Close the application window to exit the Sudoku solver.

## Techincal Frameworks

- Pygame library
- Requests library
- JSON library
