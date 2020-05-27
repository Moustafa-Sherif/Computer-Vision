 # Image Stitcher
 

 - It's the same idea of creating a panorama scene from your camera 
 - If you have two images with common points you can get these points and merge both in one image 
 - We have implmented this on two steps 
	 - getting common points 
		 - Chooseing them manually , you can notice the blue circles at the two images![](images/first%20image.jpg) ![](images/second%20image.jpg)
		 - using SIFT Algorithm (we have used Open cv method for that)![](images/Keypoint%20detection.jpg)
		 - size in the image means how much the algorithm sure It's a matching point
	 - getting hemography matrix 
		 - Hemography Matrix is the matrix mapping from one image plan to  the other image
		 - you can get this by using least square solution(numpy imlpmention)
		 - method called numpy.linalg.lstsq()
		 - intuition behind it is solving linear equation but in Matrix version
 - Result ![](images/panorama.jpg)
 - credits
	- [Zeyad Ezzat](https://github.com/zeyad3ezzat)
	- [Mostafa Tohami](https://github.com/tohamybasha)
