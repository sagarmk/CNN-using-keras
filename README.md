## MNIST handwritten digit recognizer
---
- Dataset:
![Image Title](https://raw.githubusercontent.com/sagarmk/CNN-using-keras/master/images/f1.png) 
- Ran three models:


	- MLP based model


	- Simple Convolutional Neural Network using dropout regularization:
		- Performs better than MLP based model
		- The layer has 32 feature maps, which with the size of 5×5 and a rectifier activation function. 
		- Next we define a pooling layer that takes the max called MaxPooling2D. 
		- The next layer is a regularization layer using dropout configured at 20%.
		- Flatten layer.
		- Next a fully connected layer with 128 neurons and rectifier activation function.
		- Finally, the output layer has 10 neurons for the 10 classes and a softmax activation function to output probability-like predictions for each class.


	- Largers Convolutional Neural Net with dropout regularization:
		- Convolutional layer with 30 feature maps of size 5×5.
		- Pooling layer taking the max over 2*2 patches.
		- Convolutional layer with 15 feature maps of size 3×3.
		- Pooling layer taking the max over 2*2 patches.
		- Dropout layer with a probability of 20%.
		- Flatten layer.
		- Fully connected layer with 128 neurons and rectifier activation.
		- Fully connected layer with 50 neurons and rectifier activation.
