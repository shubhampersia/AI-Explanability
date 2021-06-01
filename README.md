# AI-Explanability

## Overview and Procedure

This is a ML model to predict that an instance(image) belongs to a certain class. We will be using InceptionV3, a pretained model in Keras library to predict the Dog as a labrador. We will also be creating our own model for the same classification.

Step 1: Import the following libraries
* numpy
* skimage
* sklearn
* warnings
* copy

Step 2: Initialize the pretained Keras model InceptionV3

Step 3: Read and preprocess the image

Step 4: Predict class of Input Image.

## Implementation

* Extracting superpixels and creating random pertubations of the image.
* Using ML classifier to predict classes of new generated images.
* Computing distances between the original image and each of the perturbed images and compute weights of each perturbed image by using a kernel.
* Using perturbations, predictions and weights to create an explainable model with the help of Linear Regression.

## Results 
This is the image to be Classified <br> <br>
<img src="https://github.com/deadpool221b/AI-Explanability/blob/main/cat-and-dog.jpg"> <br> <br>
These are the areas which were involoved in the prediction of the image to "Labrador" <br> <br>
<img src="https://github.com/deadpool221b/AI-Explanability/blob/main/Regions-Involved.png">
## References

* <a href="https://towardsdatascience.com/classify-any-object-using-pre-trained-cnn-model-77437d61e05f"> InceptionV3 </a>
* <a href="https://medium.com/@darshita1405/superpixels-and-slic-6b2d8a6e4f08"> Superpixel Segmentation </a>
* <a href="https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html"> Linear Regression </a>


