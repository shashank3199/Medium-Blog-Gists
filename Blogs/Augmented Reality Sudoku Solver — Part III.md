# Augmented Reality Sudoku Solver — Part III -

The following are the Gist Links used in the blog post -

|                                                Gist Title                                                | Remarks |
|:--------------------------------------------------------------------------------------------------------:|---------|
| [pytorch_gpu_util_functions.py](https://gist.github.com/shashank3199/3ac15b86c06f54dd8d9390577d4c5361) | <b>GPU Device Utility Functions</b>: These functions are used to determine the available computational device and allocate the object on the device.       |
|   [pytorch_gpu_util_class.py](https://gist.github.com/shashank3199/ce7c1ea5d2713522950a864013c1e5c2)   | <b>DeviceDataLoader Class</b>: The class is a supplement to the DataLoader Class and is used to allocate the DataLoader members on the available device.       |
|    [sudoku_classifier_f1.py](https://gist.github.com/shashank3199/68915a27156a2cb5eb2c740521944cdc)    | <b>Accuracy</b>: This Method is used to calculate the accuracy of the predictions from the model.       |
|    [sudoku_classifier_c1.py](https://gist.github.com/shashank3199/ee9d218f1591a665f99fbe32f92ed55b)    | <b>Char74kModel Class</b>: This is an extension of the `torch.nn.Module` class and is used to build a custom model for our specific goal.       |
|    [sudoku_classifier_c2.py](https://gist.github.com/shashank3199/4680c0c88a55b7845afbe809921b5ac1)    | <b>Model Weight Initialization</b>: This method is used to initialize the weights and biases of the feature exctraction layers.       |
|    [sudoku_classifier_c4.py](https://gist.github.com/shashank3199/ca061eaff3786ad26880902f8501ec04)    | <b>Forward Pass</b>: This method defines the feed forward pass step from one layer (or sequence of layers) to another.       |
|    [sudoku_classifier_c5.py](https://gist.github.com/shashank3199/f98a30da7a3595776e7a4c35fe76258a)    | <b>Training Step</b>: This method defines the process used in an itertion for a training batch.       |
|    [sudoku_classifier_c6.py](https://gist.github.com/shashank3199/bb5d6f8672c3dddf7b896336585eb894)    | <b>Validation Step</b>: This method is analogous to the Training Step with the difference that this step caluclates the accuracy as well.       |
|    [sudoku_classifier_c7.py](https://gist.github.com/shashank3199/15d99354bc23dbe28839c4d6ae000595)    | <b>Validation Epoch End</b>: This method calculates the mean accuracy and loss for an epoch.       |
|    [sudoku_classifier_c8.py](https://gist.github.com/shashank3199/74ce3be7b54fa4777cc4d849c022bd93)    | <b>Epoch End</b>: This method is used to print the Validation Step paramters in a specific format.       |
|    [sudoku_classifier_f2.py](https://gist.github.com/shashank3199/2bdbfef6ec1e37862edfdd35d89ae798)    | <b>Evaluate Model</b>: This method is used to display the metrics of a model over a Test/Validation DataLoader.       |
| [sudoku_classifier_f3.py](https://gist.github.com/shashank3199/6035ac5ad50aad5a7c8d3faf451e9f36)       | <b>Fit Model</b>: This method is used to perform model fitting over a Training DataLoader using an optimizer and learning rate scheduler.       |
| [sudoku_classifier_f4.py](https://gist.github.com/shashank3199/0fcf8829877b737360d87dbaf523635a)       | <b>Train Model</b>: This is the "Main" driver method used to train the model and save its weights.       |
| [sudoku_classifier_f5.py](https://gist.github.com/shashank3199/95a7cc888304b87f96bde3afd8481eea)       | <b>Evaluated Saved Model</b>: This method is used to load model weights from a file and then evaluate its metrics.       |
| [sudoku_classifier_f6.py](https://gist.github.com/shashank3199/a98821aa9407c4d64a41a936b2872ab3)       | <b>Load Model</b>: This method is used to load model weights from a file and return the model.       |