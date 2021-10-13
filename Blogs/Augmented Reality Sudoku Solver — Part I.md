# Augmented Reality Sudoku Solver: Part I -

The following are the Gist Links used in the blog post -

|                                           Gist Title                                          | Remarks |
|:---------------------------------------------------------------------------------------------:|---------|
| [sudoku_logic_c1.py ](https://gist.github.com/shashank3199/94b2386b5bf62588488f78633b01e176)| <b>Sudoku Class</b>: Object-Oriented representation of the Sudoku puzzle.       |
| [sudoku_logic_c2.py ](https://gist.github.com/shashank3199/37361493ff9e5aff3424ce8d1eddfa1b)| <b>Initialize Rows and Columns</b>: Initialize Rows and Columns as doubly linked lists.       |
| [sudoku_logic_c3.py ](https://gist.github.com/shashank3199/abfcee8821cb08bad2e6841dcac0bd32)| <b>Solve</b>: Recursive method used to include and exclude parts of solution.          |
| [sudoku_logic_c4.py ](https://gist.github.com/shashank3199/11da122fbeb401145f5d7bb23b5c7d8f)| <b>Cover Column</b>: Operation to <i>Include</i> a column and associated row elements from the solution space.        |
| [sudoku_logic_c5.py ](https://gist.github.com/shashank3199/a140444c7c16f35095c8cf49d90c78e6)| <b>Uncover Column</b>: Operation to <i>Exclude</i> a column and associated row elements from the solution space.       |
| [sudoku_logic_c6.py ](https://gist.github.com/shashank3199/84fbd4f18780df4d247085f6d6691a42)| <b>Get Solutions</b>: The "Main" function of the Sudoku class object used to return all possible solutions of th puzzle.       |
| [sudoku_logic_c7.py ](https://gist.github.com/shashank3199/cb01b6194224e3c64eed47322697723f)| <b>Element Possible</b>: Utility method used to check if an element is valid for a specific position in the puzzle.          |
| [sudoku_cli_main.py ](https://gist.github.com/shashank3199/b7642b946235e4024dfcd76941ddc7ed)| <b>Main</b>: The "Main" Function of the Program used to initialize the Sudoku class object and print the puzzle solutions.       |