# augment_height
Python script to augment thermal drones images and labels in the darknet format to simulate different operation altitudes.

The function takes three arguments, the starting height of the input data in units of distance, the ending height of the simulated data in the same units of distance and the input image filetype.

When executed in a folder containing thermal images and labels, it outputs the augmented images and labels into a folder with the name 'data_START_END' where START and END are the inputted function values.
