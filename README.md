# Overview of the whole notebook

The code snippets provided consist of the most well-known convolutional neural network (CNN) architectures implemented using the Keras library.

## LeNet-5

The first code part implements the LeNet CNN architecture, which is one of the earliest CNN models. 
One of the earliest successful CNN architectures developed in the 1990s by Yann LeCun for handwritten digit recognition. 
It consists of two sets of convolutional and pooling layers followed by three fully connected layers. 
The LeNet model is primarily used for digit recognition tasks.

## AlexNet: 
    
The second code part implements the AlexNet CNN architecture, which won the ImageNet Large Scale Visual Recognition Challenge in 2012.
It was the first deep CNN architecture that achieved state-of-the-art performance on the ImageNet dataset. 
It consists of five convolutional layers, three fully connected layers, and two dropout layers.

## VGG16 and VGG19: 
    
The third code part implements a CNN architecture using multiple VGG blocks. These CNN architectures were developed by the Visual Geometry Group at the University of Oxford in 2014. They are known for their simplicity and their success in the ImageNet Large Scale Visual Recognition Challenge (ILSVRC) competition.
 The VGG model consists of 16 to 19 layers, which are mainly composed of convolutional layers followed by max-pooling layers.

## Naive Inception/GoogLeNet and Inception-v3: 

The fourth code part implements a CNN architecture using a naive inception module.
It was developed by Google researchers in 2014, this architecture introduced the Inception module that allowed for more efficient computation and deeper networks. 
The inception module consists of multiple convolutional layers with different kernel sizes concatenated at the end.

## ResNet: 

It was Developed by Microsoft researchers in 2015. 
ResNet (short for Residual Network) introduced the concept of skip connections to help overcome the problem of vanishing gradients in deep networks.
 
    
Each of these architectures has unique features. All these models have achieved high accuracy in our image classifcation task which is a computer vision task.
These architectures have played a significant role in advancing the field of computer vision and have been used as the basis for many subsequent architectures.

Note : we add in this application the use of other CNN architectures which are : 
        
* DenseNet: Developed by researchers at Facebook AI Research in 2016, DenseNet introduced the concept of dense blocks where every layer is connected to every other layer in a feed-forward manner. This architecture has shown to be highly efficient and effective in image classification tasks.

* EfficientNet: Developed by Google researchers in 2019, EfficientNet uses a novel compound scaling method to optimize the depth, width, and resolution of the network. It has achieved state-of-the-art performance on the ImageNet dataset while using fewer parameters and less computation than previous architectures.


 
