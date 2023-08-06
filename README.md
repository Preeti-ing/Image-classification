# Image-classification
Classification of image using CNN and Keras (CIFAR-10 dataset) 

What is CNN?

CNN stands for convolutional neural networks which is basically an architecture for image classification.

How does CNN help in image classification?

CNNs effectivly classifies image because they are able to automatically learn the spatial hierarchies of features, such as edges, textures, and shapes, which are important for recognizing objects in images.

Layers in a neural network:-
1) The input layer is the first layer in the network and it is where the input data is fed into the network. The input layer does not perform any computation, it simply receives the input and passes it on to the next layer.
2) The hidden layers are the layers that come after the input layer and before the output layer. These layers perform the bulk of the computation in the network, such as feature extraction and abstraction. 
3) The output layer is the final layer in the network and it produces the output of the network.
   
HOW IT WORKS

CNNs consist of a series of interconnected layers that process the input data. The first hidden layer of a CNN is usually a convolutional layer, which applies a set of filters to the input data to detect specific patterns. Each filter generates a feature map by sliding over the input data and performing element-wise multiplication with the entries in the filter. These feature maps are then combined and passed through non-linear activation functions, such as the ReLU function, which introduces non-linearities into the model and allows it to learn more complex patterns in the data.

Subsequent layers in a CNN may include additional convolutional layers, pooling layers, and fully-connected layers. Pooling layers reduce the size of the feature maps. This helps reduce the overall number of parameters in the model and makes it more computationally efficient. Fully-connected layers are typically found after convolutional and pooling layers of a CNN. A fully-connected layer connects all the neurons in a layer to all the neurons in the next layer, allowing the model to learn possible non-linear combinations of the features learned by the convolutional layers.

The final layer of a CNN is typically a softmax layer, which produces a probability distribution across the possible class labels for the input data. The class that has the highest probability is chosen as the prediction of the model.

Real time usage of image classification- in self driving cars, security system, traffic control systems, etc.


PROCESS- 

