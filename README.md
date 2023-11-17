## Generating and solving sudokus with Clingo!
This repository contains Clingo code for generating and solving sudokus. The repository contains code to solve sudokus using standard Clingo contraints. The repository contains code to generate sudokus with unique solutions using the "saturation" principle. 

Cells are denoted by cell(R, C, N) where R is row, C is column and N is the value of the cell. The constant k denotes how large the squares are and how many total squares there are (default: 3).

Particularly interesting is the addition of the "Bomb" and "Knight" constraint. Try to find out what exactly they do! :)
