# Circle-Detection-
Circle Detection 
Given an image find whether the image has a circular region and if so evaluate the given pixel is inside that circular region The sample images are given in "circles" folder.

First i import all relevant libraries opencv and numpy then i read the image using Cv2 and i tried to show the output as the copy of image we imported.
I used HoughCircles function from opencv to solve this problem.first I have converted the input image to greyscale.Then I applied HoughCircles function to the image and adjusted the parameters for the best results.
