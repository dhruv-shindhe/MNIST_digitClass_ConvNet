# MNIST_digitClass_ConvNet
Classification of handwritten digits from the MNIST data set using Convolution neural network Using the LeNet architectur .
The model had 2 convolutional layers with 30 (5,5) fitlers in the first and 15 (3,3) filters ,it has 2 maxPooling layers of size (2,2) with a stride of 1 and no padding .
It also has a dropout layer with a droupout of 50%
The model was tested using a image of a digit created using paint and was found to classify it with an accuracy of 98 %

Additionally Models API from keras was used to view the output after passing through the convolutional layers which helps us to kow with feature are given more prefernce in the image.
