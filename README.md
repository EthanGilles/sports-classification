# Sports Image Classification with Convolutional Neural Networks

### Authors: Ethan Gilles, Josh Thyng, Sam Fickett
### Course: COS470 - Image Processing and Computer Vision
### University: University of Southern Maine
### Fall 2024

## Project Overview

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images 
of various sports. The primary objective is to develop a model that can accurately identify the 
sport being played in a given image. By leveraging deep learning techniques and image processing, 
our project demonstrates how neural networks can be applied to real-world classification problems 
within sports and computer vision domains.

## Project Goals

Implement a CNN that will work on videos for accurate predictions of a sport using a livestreaming service. We accomplished this
by adding a script that that takes in an mp4 file and will output a prediction of the sport using  an average of the predictions on individual frames.

## Dataset

Our dataset consists of images labeled across 100 different sports categories, 
providing a diverse range of activities for classification. The dataset includes 
a total of 13,492 images for training, with additional subsets for validation 
and testing to measure model performance. Each class captures various aspects of 
a sport, with sports like:

- Basketball
- Football
- Soccer
- Tennis
- Baseball
- Swimming

And a lot of lesser known sports, like:

- Chuck Wagon Racing
- Underwater Cycling
- Axe throwing
- Ice Yachting
- And many more...

The images vary in style, lighting, and perspective, making this dataset 
well-suited for training a robust model that can generalize across real-world 
sports images. We applied preprocessing and data augmentation techniques to 
enhance model performance and prevent overfitting.

## Notebook

The notebook called  `training` has the model along with all of the cells used for training and testing the model.

The notebook called `video-prediction` will make a prediction on any mp4 video for the sport found within it. 

## Results

After pre-processing our input images looked like this:

![pre-processed data](https://github.com/EthanGilles/sports-classification/blob/b89c7ea34ec258d9308d8ef1b9e3aa1651179ff2/results/Pre-processing.png)

Our model's final parameters were:

![model parameters](https://github.com/EthanGilles/sports-classification/blob/b89c7ea34ec258d9308d8ef1b9e3aa1651179ff2/results/Model.png)

Our training loss graph:

![training loss](https://github.com/EthanGilles/sports-classification/blob/b89c7ea34ec258d9308d8ef1b9e3aa1651179ff2/results/Training.png)

Model accuracy:

![accuracy](https://github.com/EthanGilles/sports-classification/blob/b89c7ea34ec258d9308d8ef1b9e3aa1651179ff2/results/Accuracy.png)

Confusion Matrix:

![confusion matrix](https://github.com/EthanGilles/sports-classification/blob/b89c7ea34ec258d9308d8ef1b9e3aa1651179ff2/results/Confusion-Matrix.png)

