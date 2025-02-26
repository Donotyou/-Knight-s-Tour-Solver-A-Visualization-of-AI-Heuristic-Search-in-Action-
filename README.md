Knight's Tour Solver

Overview

The Knight's Tour Solver is a Python-based graphical application that visualizes and solves the Knight's Tour problem using Warnsdorff's heuristic. It employs the Tkinter library for the GUI and provides an interactive way to explore the path of a knight on an n x n chessboard.

Features

Interactive user input for board size and starting position.

Implementation of Warnsdorff's heuristic for optimized pathfinding.

Real-time visualization of the knight's movement.

Step-by-step graphical representation with an animated path.

Error handling and user-friendly messages.

Installation

Prerequisites

Ensure you have Python 3.x installed on your system. The following dependencies are required:

pip install tk

Usage

Run the script:

python knights_tour.py

Enter the board size (n x n).

Specify the knight's starting row and column.

Observe the real-time visualization of the knight's tour.

Algorithm

The implementation follows Warnsdorff’s Rule, a heuristic method that selects the next move with the least onward moves, increasing the likelihood of completing the tour successfully.

Code Structure

KnightTour: Implements the knight's movement logic and heuristic-based pathfinding.

KnightTourApp: Manages the GUI interaction and visualization using Tkinter.

find_knight_tour(): Recursively finds a valid knight’s path using backtracking.

update_canvas(): Dynamically updates the chessboard visualization.

Example Output

After inputting parameters, the knight's tour is visually displayed in a separate window, showing the knight's movement sequence with a numbered path.

Limitations

The algorithm works well for small to medium-sized boards but may slow down for larger sizes.

Some starting positions may not have a solution.

Contributions

Feel free to fork the repository, submit issues, or suggest improvements.

License

This project is licensed under the MIT License.

Author: [DOnotyou]

