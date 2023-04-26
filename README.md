# Cnn Classification
Classification with Convolutional Neural Network (CNN) on images and gene data.

## CIFAR-10 - Image Dataset
The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

- Info: https://www.cs.toronto.edu/ kriz/cifar.html
- Download: https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz

Use 7-zip to extract .gz, then .tar files to get data batches.
Data batches are Python "pickled" objects produced with cPickle.

## MNIST - Handwriting Dataset
The dataset has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image. It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting.

- Info: https://learn.microsoft.com/en-us/azure/open-datasets/dataset-mnist?tabs=azureml-opendatasets 
- Download: http://yann.lecun.com/exdb/mnist/

## Cho - Gene Dataset
The dataset is collected from UCI machine learning repository. 
Each row represents a gene:
1) The 1st column is gene_id
2) The 2nd column is the ground truth clusters. You can compare it with your results. "-1" means outliers.
3) The rest columns represent gene's expression values (attributes).

- Download: https://github.com/lin-shuang/cnn-classification/blob/main/data/cho.txt