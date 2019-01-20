# Transfer-Learning-densenet121
Performed classification on images of cats and dogs, using pretrained densenet121.

## Transfer Learning

Transfer learning is a machine learning method where a model developed for a task is reused as the starting point for a model on a second task.

It is a popular approach in deep learning where pre-trained models are used as the starting point on computer vision and natural language processing tasks given the vast compute and time resources required to develop neural network models on these problems and from the huge jumps in skill that they provide on related problems.
 
 ## Imagenet
 
ImageNet is an image database organized according to the WordNet hierarchy (currently only the nouns), in which each node of the hierarchy is depicted by hundreds and thousands of images.
### Densenet
Dense Convolutional Network (DenseNet), which connects each layer to every other layer in a feed-forward fashion. Whereas traditional convolutional networks with L layers have L connections — one between each layer and its subsequent layer — our network has L(L+1)/ 2 direct connections. For each layer, the feature-maps of all preceding layers are used as inputs, and its own feature-maps are used as inputs into all subsequent layers. DenseNets have several compelling advantages: they alleviate the vanishing-gradient problem, strengthen feature propagation, encourage feature reuse, and substantially reduce the number of parameters.
[Densenet Models Pytorch](https://pytorch.org/docs/0.4.0/_modules/torchvision/models/densenet.html)

## About the Dataset
The data consists of images of cats and dogs. This data is taken from kaggle, and has been further broken down into training and testing set (directories) which further contains the images of cats and dogs in separate folder , with corresponding name.

