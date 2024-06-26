![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-orange)
![Python](https://img.shields.io/badge/Python-3.6+-blue)
![License](https://img.shields.io/badge/License-MIT-green)

# Image Classifier using TensorFlow
This repository contains an image classifier project built with TensorFlow, utilizing both Multi-Layer Perceptron (MLP) and Convolutional Neural Network (CNN) models. The project demonstrates that the CNN model achieved better accuracy in recognizing digits compared to the MLP model, with less number of parameters. 

## Project Overview
This project involves training image classifiers on a dataset of digit images. The primary goal is to compare the performance of MLP and CNN models in digit recognition tasks, using the loss function and accuracy. The models were built and trained using TensorFlow, a powerful deep learning framework.

## Data 
The data used in this project comes from the Street View House Numbers [SVHN](http://ufldl.stanford.edu/housenumbers/) Dataset. SVHN is a real-world image dataset designed for developing machine learning and object recognition algorithms with minimal requirements for data preprocessing and formatting. It is similar to the MNIST dataset, containing small cropped images of digits, but with significantly more labeled data—over 600,000 digit images. The dataset presents a more challenging and realistic problem, as it involves recognizing digits and numbers in natural scene images obtained from house numbers in Google Street View images.

## Results
After training and evaluating both models, the results show that the CNN model provided better approximations and higher accuracy in digit recognition than the MLP model. The CNN's ability to capture spatial hierarchies in images makes it more suitable for this task.

### Accuracy MLP model
![image](https://github.com/DavidCastro88/CNNImageClassifier/assets/91480088/0e19bbfe-a49e-4f03-88e8-f64f07db6fcf)
### Accuracy CNN model
![image](https://github.com/DavidCastro88/CNNImageClassifier/assets/91480088/1d1adf0c-aa1b-4595-89a8-2f4c22b089d7)


### Predicts MLP model
![image](https://github.com/DavidCastro88/CNNImageClassifier/assets/91480088/db3aca66-3e01-4d12-aca3-8046f6618552)
### Predicts CNN model
![image](https://github.com/DavidCastro88/CNNImageClassifier/assets/91480088/348dd4ea-2fa1-43fb-8f58-1f2c1049e702)

```CNNImageClassifier.ipynb```: The main notebook for building, training, and evaluating the image classifiers.

```assignments/```: A directory containing example notebooks demonstrating various TensorFlow functionalities.
