# Stereo-Vision
Stereo Vision using two methods Block Matching &amp; Dynamic programming.

# 1 Block Matching
To get the disparity value at each point in the left image, you will search over a range disparities, and compare the windows using two different metrics mentioned in class: Sum of Absolute Differences (SAD) and Sum of Squared Differences. Do this for windows of size w w where w = 1, 5 and 9. The disparity, d, is restricted to be in range DdD. For this assignment we will use D = 8. You should try at least 2 pairs of images and for each show for each window size and each metric disparity image.


# 2 Dynamic programming
# 2.1 Disparity computation
Repeat the process explained above fore each row of the image and compute the disparity maps
for image pairs.
