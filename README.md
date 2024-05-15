# Image-Classification-with-ResNet
This is a CECS 550 Pattern Recognition course project. 

In this project,  implemented a variant of the Residual Network (ResNet) architecture, which is renowned for its effectiveness in deep learning tasks, particularly in the domain of image classification. ResNet models are designed to handle the vanishing gradient problem that often occurs with traditional deep convolutional neural networks by introducing residual connections (also known as skip connections).

Key Features of the ResNet Model:
Residual Blocks: The core idea behind ResNet is its use of residual blocks. These blocks have skip connections that bypass one or more layers. Typically, a residual block contains two or three convolutional layers, and the input to the block is added to its output. This setup helps in training deeper networks by enabling the gradient to flow directly through the skip connections across layers without diminishing.

Enhanced Training Efficiency: By allowing gradients to flow through the network without hindrance, ResNet models can be trained much deeper without the risk of gradient vanishing. This quality makes them highly effective for learning from vast amounts of data and achieving high accuracy in complex visual recognition tasks.

Adaptability: Although originally designed for image recognition, ResNet's flexibility allows it to be adapted for various other tasks in computer vision and beyond, making it a versatile choice for many deep learning applications.

Model Configuration:
For our project, we utilized a modified version of ResNet suitable for the CIFAR-10 dataset. The configuration involved:

Layers: The model was structured with multiple ResNet blocks, each comprising convolutional layers followed by batch normalization and ReLU activation. The specific number of layers and their arrangement was tailored to balance between computational efficiency and learning capability.
Output: The network culminated in a global average pooling layer followed by a dense layer with softmax activation to classify images into one of ten categories.

Performance:
The ResNet model demonstrated robust performance on the CIFAR-10 dataset, achieving considerable accuracy and providing deep insights into the classification of various image categories. Its success in our project underscores the model's reliability and efficiency in handling complex image recognition tasks.
