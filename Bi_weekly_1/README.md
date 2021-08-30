## Biweekly Report 09/08/21

## Brian Cain 

### Report Goals:
The goal of this initial bi-weekly report is to better understand the concepts covered over the first weeks of Applied Deep learning. These concepts include understanding through the application of covered concepts in Convolutions, feature learning, multi-layered perceptrons and dropout. 

### Data Used:
For these exercises we will start out using the CIFAR-10 dataset. This dataset can be found at this location: http://www.cs.toronto.edu/~kriz/cifar.html. This datast is used as it will expose us to 10 different classes that we would like to output probabilities for. It will as well serve as an appropriate introduction to classifying images based off the methods already covered in this course. 

### EDA_Image_Convolutions.ipynb:
The purpose of this script is to perform exploratory data analysis on creating convolutional filters over an image and as well perform some pooling operations to visualize what effects convolutions have on the actual image data. 

### Feature_Comparison.ipynb:
The purpose of this script is to create a convolutional neural network that performs its own feature learning through applying convlutional filters and pooling operations over an image. We will then create a model that uses hand-crafted features from image tensors without the aid of applying filters. We will compare the results of the convolutional feature learning approach with more traditional feature engineering hand-crafted approach. 

### Dropout_Comparison.ipynb:
In this script, we will utilize the dropout learning technique on our dataset using the convolutional neural network created in Feature_Comparison.ipynb. We will then train a similar convolutional neural network but using dropout. We will perform EDA to compare the performance/over-fitting of the models on our image dataset. 
