# SudokuSolver
Declan Galleher

A python sudoku solver that uses the ac-3 algorithm to solve sudoku puzzles.

To run give the filename of a text file containing a list of sudoku puzzles formatted with one puzzles per line in the file
Each line should be a sequence of numbers for the already solved cells and "." for any unsolved cell

For example a puzzle like this:

|3..|2..|...|

|...|1.7|...|

|7.6|.3.|5..|

–––––––––––––

|.7.|..9|.8.|

|9..|.2.|..4|

|.1.|8..|.5.|

–––––––––––––  

|..9|.4.|3.1|

|...|7.2|...|

|...|..8|..6|

should be written as: 3..2........1.7...7.6.3.5...7...9.8.9...2...4.1.8...5...9.4.3.1...7.2........8..6
and will have the solution

|351|286|497|

|492|157|638|

|786|934|512|
–––––––––––––
|275|469|183|

|938|521|764|

|614|873|259|
–––––––––––––
|829|645|371|

|163|792|845|

|547|318|926|

The file of puzzles euler.txt was sourced from https://projecteuler.net/problem=96
