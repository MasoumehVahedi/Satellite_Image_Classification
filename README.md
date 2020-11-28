# Satellite_Image_Classification

# Planet: Understanding the Amazon from Space

# Introduction

In this project, I applied deep learning neural network to classify satellite images. As Convolutional Neural Network (CNN) method is a well-known technique for image classification, I have worked on this method to show how I can classify satellite images.
The aim of this project was to identify the performance of CNN model for satellite image processing. The folders contain:
•	Data Analysis and Exploratory
•	Deep learning
Note: I loading only first 2000 images to run the model for memory reasons

# Content

In this practice, 4 CNN models have been trained including:
1-	CNN model without dropout and data augmentation;
2-	CNN model with dropout regularization;
3-	CNN model with image data augmentation;
4-	Transfer learning/ pre-trained CNN model VGG16;
and then the accuracy of these techniques were compared.

# Convolutional Neural Network Architecture

The CNN method is one of the deep learning algorithm which can take an image and differentiate the features from each other. In this method, a ConvNet using the specific filters (so-called wavelet) move through the image and extract the features that not only can lead to reduction of the number parameters, but also can simplify the sophistication of image. The structure of a basic CNN has been shown in Figure 1:
image
Figure 1. An example of CNN architecture (2)

File formats

•	train.csv - a list of training file names and their labels
•	sample_submission.csv - correct format of submission, contains all the files in the test set
•	[train/test]-tif-v2.tar.7z - tif files for the training/test set
•	[train/test]-jpg[-additional].tar.7z - jpg files for the trainin/test set
•	Kaggle-planet-[train/test]-tif.torrent - a BitTorrent file for downloading [train/test]-tif-v2.tar.7z

# Dataset

The planet Amazon dataset is available in Kaggle website: https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/data

# Reference

1-	https://nbviewer.jupyter.org/github/connormca12/Springboard-Projects/blob/master/capstone-2/notebooks/machine_learning.ipynb
2-	https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53
