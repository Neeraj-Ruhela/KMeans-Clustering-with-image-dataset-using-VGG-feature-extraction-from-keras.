# Knn-Clustering-with-image-dataset-using-VGG-feature-extraction-from-keras.
Image clustering is an essential data analysis tool in machine learning and computer vision. Many applications such as content-based image annotation and image retrieval can be viewed as different instances of image clustering. Technically, image clustering is the process of grouping images into clusters such that the images within the same clusters are similar to each other, while those in different clusters are dissimilar.

VGG is a convolutional neural network model for image recognition proposed by the Visual Geometry Group in the University of Oxford, where VGG16 refers to a VGG model with 16 weight layers, and VGG19 refers to a VGG model with 19 weight layers. The architecture of VGG16: the input layer takes an image in the size of (224 x 224 x 3), and the output layer is a softmax prediction on 1000 classes. From the input layer to the last max pooling layer (labeled by 7 x 7 x 512) is regarded as the feature extraction part of the model.

Here we are implementing the K-means clustering algorithm for clustering the images that have three classes. The classes include Zebra, Lion, and Fish. 

Shared code will use the labels obtained from clustering and will save the test images in the different folders(respective clusters).
For dataset, please comment your email id.
