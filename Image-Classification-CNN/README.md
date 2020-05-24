# Image-Classification-CNN
 

 ## Main Points
	 - Simple Project to classify image for cifar dataset
	 - we have implemented google net archetchre 
	 - We have implemented Inception V1 , V2 
	 - all implmentation done in pytorch 
	 - We have reached 84% accuracy on validation set 
	 - We have reached 80% accuracy on Testing set 
	 - No Transfer Learning used 

## Dataset discription:

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6000 images per class. The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks.

## Convolutional Neural Networks (CNNs)
Convolutional neural networks (CNNs) are a special kind of neural networks for processing data that has a known grid-like topology such as time-series data and image data. The general structure of a CNN consists of one or more convolutional layers followed by one or more fully connected layers as in a standard multi-layer neural network as illustrated in Figure 2. This constrained architecture allows the CNN to leverage the spatial and temporal structure of the input and allows the network to learn more complex features from different parts of the input.
Typically, a convolutional layer consists of three stages:

 1. In the first stage, the layer applies a kernel to its input by performing several convolutions in parallel to produce a set of linear activations.
 2. In the second stage, each linear activation is run through a nonlinear activation function, such as the recti ed linear activation function.
 3. In the third stage, a pooling function is used to further modify the output of the layer. Pooling functions replace the output of the net at a certain location with a summary statistic of the nearby outputs. For example, the max pooling operation reports the maximum output within a rectangular neighborhood. Other popular pooling functions include the average of a rectangular

 

