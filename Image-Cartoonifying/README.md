
# Image-Cartoonifying

 - In this problem set we want to make the real-world images look like they are genuinely from a cartoon
 - The basic idea is to fill the flat parts with some color and then draw thick lines on the strong edges. In other words, the flat areas should become much more flat and the edges should become much more distinct.
 - We will detect edges and smooth the flat areas, then draw enhanced edges back on top to produce a cartoon or comic book effect.
 - this project is easily understable from the notebook
 - Steps to get the output
	 
	 1.transfer image to grey scale
	 
	 2.apply median filter to the previous output
	 
	 3.applu laplacian filter to the previous output
	 
	 4.apply threshold to previous output
	 
	 5.apply bilateral filter to previous output
	 
	 6.apply bilateral filter to the original input
	 
	 7.apply bitwise and  between the output from 5 and 6
	 
	 8.the result image from 7 will be the cartoon image
	 
	 ![](images/Before%20and%20After.jpg)
	 


	 
