# Siamese Network with VGG-16

## Description
This project implements a **Siamese Network** based on **VGG-16** for **image similarity recognition** on the **Fashion-MNIST** dataset. The goal of the project is to compare images and determine their similarity using the **Siamese** network architecture.

The project also incorporates **t-SNE** for visualizing the model's results, as well as demonstrating how similar images can be found for a given query image.

## Usage
###  Loading and Preparing the Data
The project uses the Fashion-MNIST dataset for training the model
### Creating Image Pairs for Training
The project generates pairs of images for training the network. One pair belongs to the same class (label 1), and the other pair belongs to different classes (label 0)
#### Example of work 
![alt text](image.png)
### Implementing Siamese Network Using VGG-16
Creating a Siamese Network model using VGG-16 for image comparison
#### Training the Model
The model is trained on the generated image pairs, using accuracy and binary crossentropy metrics for evaluation
#### Visualizing with t-SNE
I use t-SNE to visualize the training results in a 2D space
![alt text](image-1.png)
### Results
#### Test Accuracy
After training the model, we evaluate it on the test set and obtain the accuracy 

Test Loss: 0.1499
Test Accuracy: 0.9449
#### Example Output
The model compares images and determines their similarity
![alt text](image-2.png)



![alt text](image-3.png)



![alt text](image-4.png)