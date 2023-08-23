# Dogs-and-Cats-Classification-CNN-model
Deep Learning Classification Model based on Convolution Neural Network(CNN) Algorithm.

**Objective:**

The main objective of this project is build a deep learning model, that can classify dogs and cats images effortlessly.

**About Dataset:**

This is a binary classification datatset of two classes: dogs and cats.
* **Total number of images in the dataset: 3000**
* Total number of images of dogs in the train directory:  1000
* Total number of images of cats in the train directory:  1000
* Total number of images of dogs in the validation directory:  500
* Total number of images of cats in the validation directory:  500

**Algorithm:**

Convolution Neural Network(CNN) is a type of Deep Learning neural network architecture commonly used in Computer Vision. CNNs are inspired by the way the visual cortex works in the human brain.

CNNs consist of a series of layers, each of which performs a specific task. The first layer is the convolutional layer, which applies filters to the input image to extract features. The filters are small, 2D arrays of weights that are learned during the training process. The convolutional layer produces a set of feature maps, each of which represents a different feature of the image.

The next layer is the pooling layer, which downsamples the feature maps to reduce the amount of computation required. The pooling layer can be either max pooling or average pooling. Max pooling takes the maximum value from each region of the feature map, while average pooling takes the average value.

The final layer is the fully connected layer, which is a traditional neural network layer that makes the final prediction. The fully connected layer takes the output from the pooling layer and connects it to a set of output neurons, one for each possible class.

**Language and library:**

Language: Python 3.11.4

Library: tensorflow and matplotlib
