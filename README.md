# TransferLearning_CAM

This repository includes two Jupyter notebooks. The first one retrains the pre-trained ResNet-50 using transfer learning in order to classify the CIFAR-10 dataset.
The architecture will be adapted in order to compute the class activation maps within the second notebook. 

## Motivation
The original Matlab implementation and paper (for AlexNet, GoogLeNet, and VGG16) can be found [here](https://github.com/metalbubble/CAM).  A Keras implementation of VGG-CAM can be found [here](https://github.com/tdeboissiere/VGG16CAM-keras/blob/master/README.md).

This implementation is written in Keras and uses ResNet-50 (read the official paper [here](https://github.com/metalbubble/CAM)), which was __not__ explored in the original paper.  


## Requirements

- keras with tensorflow backend (keras version 2.0.0 or later)
- numpy
- ast
- scipy
- matplotlib
- opencv3


## Example plots



## Blog Post

This repository is discussed in the blog post [here]().


