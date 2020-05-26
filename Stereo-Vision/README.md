
# Depth Image from Stereo Vision System

 - Stereo Vision System is a computer vision prespective of having two eyes in human
 - Stereo Vision System  has two cameras and the tranformation matrix from one camera to another 
 - We are solving a base-line stereo case so 
 - base-line stereo case is the case where the images taken with a forward facing camera and the translation between cameras is along the horizontal axis .
 - three steps needs to be obtained to get the depth
	 - Block Matching 
	 - Calclating the desparity for a row 
	 - apply the same calclation for all rows in the image
 - Block Matching 
	 - We calclated Matched points using Sum of Squared Differences or Sum of Absolute Differences
	 - We have tried our implmentation and open-CV implmentation 
 - Disparity Calculations 
	 - The term disparity in stereo vision refers to the apparent shift in pixel or motion in a pair of stereo images.
	 - We have calcleted this using dynamic programing
	 - [lecture link](https://web.yonsei.ac.kr/hgjung/Lectures/AUE859/6.%20Stereo%20Matching.pdf)
-three steps needs to be obtained to get the depth 
 - training graphs for veriosn 2![](images/v2.jpg)
- credits
	- [Zeyad Ezzat](https://github.com/zeyad3ezzat)
	- [Mostafa Tohami](https://github.com/tohamybasha)





	
