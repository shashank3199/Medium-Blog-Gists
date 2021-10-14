# Augmented Reality Sudoku Solver: Part II -

The following are the Gist Links used in the blog post -

|                                         Gist Title                                         | Remarks |
|:------------------------------------------------------------------------------------------:|---------|
| [sudoku_cv_c1.py](https://gist.github.com/shashank3199/1f2b6cdf5df7d7f8bd4a2f60fb62f0ae) | <b>Sudoku Image Processing Class</b>: Contains the reqiured variables and methods to process our image.       |
| [sudoku_cv_c2.py](https://gist.github.com/shashank3199/82d19fad64b2b242509ede85e0e8d0bc) | <b>Detect Grid</b>:  Method used to find the largest contour and mask the area around the box with white pixels.       |
| [sudoku_cv_c3.py](https://gist.github.com/shashank3199/412c93ae28af1e94c822c849f8d50556) | <b>Apply Warp Perspective Transformation</b>: Method used to convert image from warp perspective to straight perspective.       |
| [sudoku_cv_c4.py](https://gist.github.com/shashank3199/a9faea4aee8f3bdb5bea609d1bd8198e) | <b>Get Sudoku Dimensions</b>: Get the dimensions for a sub-box in the puzzle.      |
| [sudoku_cv_c5.py](https://gist.github.com/shashank3199/0d6207217f6ee382cff617dbf1c5cad4) | <b>Pre-Process Digit Cell</b>: Preprocess the cell image to suit the CNN Model.       |
| [sudoku_cv_c6.py](https://gist.github.com/shashank3199/22db8e3f18577ebec119bc194351c17f) | <b>Get Final Matrix</b>: Method used to return the final matrix post grid and number detection.       |
| [sudoku_cv_c7.py](https://gist.github.com/shashank3199/90fb3d755593a166b626a95b9c6369db) | <b>Plot on Image</b>: Method used to draw the puzzle solution on an image.       |