# cnn-classification
Classification with Convolutional Neural Network (CNN) on image data.

## CIFAR-10 Image Dataset
The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

- Info: https://www.cs.toronto.edu/ kriz/cifar.html
- Download: https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz

Use 7-zip to extract .gz, then .tar files to get data batches.
Data batches are Python "pickled" objects produced with cPickle.
