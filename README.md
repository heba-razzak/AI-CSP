# Sudoku Solver Using Constraint Satisfaction Problem (CSP)

This project showcases a Sudoku solver built as part of an Artificial Intelligence course. The solver leverages the Constraint Satisfaction Problem (CSP) framework to efficiently find solutions to Sudoku puzzles of varying difficulty levels.

## Project Overview

Sudoku is a logic-based number placement puzzle. The goal is to fill a 9x9 grid with digits so that each column, each row, and each of the nine 3x3 subgrids contain all the digits from 1 to 9 exactly once. CSP provides a robust framework for solving such problems by breaking them down into variables, domains, and constraints.

This project demonstrates:
- Representing the Sudoku puzzle as a CSP.
- Using constraint propagation techniques to narrow down possible values.
- Implementing a backtracking search to find valid solutions efficiently.

## Features

- **CSP Implementation**: Models Sudoku rules as constraints for the CSP framework.
- **Backtracking Search**: Implements an efficient backtracking algorithm to explore possible solutions.
- **Constraint Propagation**: Uses techniques like arc consistency to reduce the search space.
- **Performance Metrics**: Tracks and reports runtime performance for solving puzzles of varying difficulty levels.

## How to Use

1. **Dataset**:
   - The notebook supports a dataset of Sudoku puzzles, which can be downloaded from [Kaggle](https://www.kaggle.com/datasets/radcliffe/3-million-sudoku-puzzles-with-ratings).

2. **Run the Solver**:
   - Open the Jupyter notebook `Sudoku_CSP.ipynb`.
   - Load a Sudoku puzzle or dataset.
   - Execute the cells to observe the step-by-step solving process and performance metrics.

3. **Customize**:
   - You can modify the code to test different puzzles or adjust solving techniques.

## Acknowledgments

- This project was completed as part of an Artificial Intelligence course.
- Thanks to the Kaggle community for the Sudoku datasets.
