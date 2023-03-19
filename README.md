# Create-Your-Own-Image-Classifier

Udacity Data Scientist Nanodegree Project 2 Create your Own Image Classifier

### Table of Contents

1. [Requirements](#requirements)
2. [Project Description(#Project Description)]
3. [Results](#results)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Requirements <a name="requirements"></a>

No specific requirements are needed for this project. 

## Project Description<a name="motivation"></a>

This project is a part of the Udacity Data Scientist Nanodegree Program. In this project, a neural network was built with evaluation on the CIFAR-10 dataset.
The project included Image Processing (Transforms), Image Augmentation, Design of a Neural Network and implementation of a training and testing pipeline for batch testing.

## Results<a name="results"></a>

Some of the benchmark results on CIFAR-10 include:

78.9% Accuracy | Deep Belief Networks; Krizhevsky, 2010

90.6% Accuracy | Maxout Networks; Goodfellow et al., 2013

96.0% Accuracy | Wide Residual Networks; Zagoruyko et al., 2016

99.0% Accuracy | GPipe; Huang et al., 2018

98.5% Accuracy | Rethinking Recurrent Neural Networks and other Improvements for ImageClassification; Nguyen et al., 2020

In comparison to these models, the neuronal network trained had an accuracy of 73.78%
The model compares suprisingly well to the model from Detectocorp's model. However, the model does not compare that well to the famous models from literature such as ResNet, AlexNet or DenseNet as the accuracy is much lower. In order to get the accuracy achieved, strategies such as Data Augmentation and Dropout were used. 

However, the high accuracy can be actually attributed to the fact that Convolution Layers with Dropout were used and Image Augmentation was performed. To do so, we can try adding more layers, changing kernel size, padding, stride, dropout, data augmentation and training the network for a longer time with addtional resources such as GPU.


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credits must be given to Udacity for providing starting code for this project.
