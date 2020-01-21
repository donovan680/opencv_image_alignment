# opencv_image_alignment
In OpenCV 3, the motion model for ECC image alignment is estimated using the function findTransformECC . Here are the steps for using findTransformECC

Read the images.

Convert them to grayscale.

Pick a motion model you want to estimate.

Allocate space (warp_matrix) to store the motion model.

Define a termination criteria that tells the algorithm when to stop.

Estimate the warp matrix using findTransformECC.

Apply the warp matrix to one of the images to align it with the other image.

Let’s dive into the code to see how to use it. 

The comments provide an explanation.
