# Augmented Reality Sudoku Solver — Part IV -

The following are the Gist Links used in the blog post -

|                                                Gist Title                                                | Remarks |
|:--------------------------------------------------------------------------------------------------------:|---------|
|    [sudoku_gui_button_c1.py](https://gist.github.com/shashank3199/465e6a68bbf73323786905dc07be608d)    | <b>Button Class</b>: This class used to display rounded rectangular buttons in pygame.       |
|    [sudoku_gui_button_c2.py](https://gist.github.com/shashank3199/04616765fb0c920ba18f51f718e55be1)    | <b>Draw Button</b>: This method is used to draw the button oer a pygame surface.       |
|    [sudoku_gui_button_c3.py](https://gist.github.com/shashank3199/02633c17be3b048e9de12e49cf6d74c3)    | <b>Button Clicked</b>: This method is used to check if the button was clicked or not.       |
|    [sudoku_gui_button_c4.py](https://gist.github.com/shashank3199/f347724f5c29762160fae8ca2d87cab7)    | <b>Button Under Mouse</b>: This method is used to check if the button is currently under the mouse position.       |
| [sudoku_gui_camerawindow_c1.py](https://gist.github.com/shashank3199/df18215a7c0c7acd90633a69acc68bf1) | <b>Camera Window Class</b>: This class is used to open the camera feed (or feed from a video) and show it in the pygame GUI.       |
| [sudoku_gui_camerawindow_c2.py](https://gist.github.com/shashank3199/c747e485edcf5c4905379a0c2ec3ccb0) | <b>Enter Camera Window</b>: This is the dunder method to enable use with the `with-context` statements.       |
| [sudoku_gui_camerawindow_c4.py](https://gist.github.com/shashank3199/721158851c6890fe2573d4e0246cb7b9) | <b>Draw Camera Window</b>: This method is used to get the feed from the camera and display the window.       |
| [sudoku_gui_camerawindow_c5.py](https://gist.github.com/shashank3199/612e46c42485e323b9183b665cc1ad0f) | <b>Exit Camera Window</b>: This is the dunder method counterpart of `__enter__`.       |
|  [sudoku_gui_gamewindow_c1.py](https://gist.github.com/shashank3199/5d8ba1ced3f29b2b0e00dde690d877b0)  | <b>Game Window Class</b>: This class is used for all the GUI components of the project.       |
|  [sudoku_gui_gamewindow_c2.py](https://gist.github.com/shashank3199/85204f4b6de018e88ca6ea41e8af5d3f)  | <b>Get Locked Box Positions</b>: This method returns the list of non-zero positions of the matrix.       |
|  [sudoku_gui_gamewindow_c3.py](https://gist.github.com/shashank3199/f7458ab7721bae320e5fa2c038bf2fd2)  | <b>Draw Game Window</b>: This method is used to display the Game Play component of the project.       |
| [sudoku_gui_gamewindow_c4.py](https://gist.github.com/shashank3199/5d27dd9792180db561580337ddcca70f)   | <b>Mouse Click Handler</b>: This method is used to handle mouse clicks during the Game Play.       |
| [sudoku_gui_gamewindow_c5.py](https://gist.github.com/shashank3199/2179b5eb55304a9e10124a9600bcd2e2)   | <b>Game Play</b>: This method defines the actions for one frame of the game play loop.       |
| [sudoku_gui_gamewindow_c6.py](https://gist.github.com/shashank3199/694ad08d2e604a52cdab628203fa8fe0)   | <b>Augmented Reality</b>: This method is used to load the Augmented Reality component of the project.       |
| [sudoku_gui_gamewindow_c7.py](https://gist.github.com/shashank3199/da2e7a20f5a023c737b8bf1dbcc2ed0e)   | <b>Main Menu</b>: This method is used to create the Main Menu for the project to navigate to Game Play and Augmented Reality.       |
| [sudoku_gui_gamewindow_c8.py](https://gist.github.com/shashank3199/02a7aafeb5900d814e7e29a15fd9cb9e)   | <b>Graceful Exit</b>: This method is used to ensure that the latest loaded puzzle matrix and its dimensions are saved before exit.       |
| [sudoku_main.py](https://gist.github.com/shashank3199/19da78d38dd97f46123f90f6c099b9c5)                | <b>Main Program</b>: This is the driver program for the project and is used to the start the rest of the code.       |