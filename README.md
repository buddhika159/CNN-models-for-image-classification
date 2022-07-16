# Image Classification using CNN and pre-trained models
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)

## Description:
This project is based on the Deeplizard course: [TensorFlow - Python Deep Learning Neural Network API](https://deeplizard.com/learn/video/RznKVRTFkBY)
This repository includes:
- Sequential model 
    - Shows how to model a Deep Convolutional NN with steps:
        - Data Preparation and Processing
        - Define a Sequential model with `Keras`
        - Train and Test
        - Inference
        - Ways to save the model
    - Model: 3-layer dense Sequential model
    - Dataset: Generated drug test experiment data population
    - Train Accuracy: `94.23%` 
    - Validation Accuracy: `95.24%` 

- CNN model for image classification
    - Dataset: [Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats/data)
        - Taking only `1,200` images out of `50,000` to train.
    - Model: 5-layer dense Sequential model
        - `Conv2D` --> `MaxPool2D` --> `Conv2D` --> `MaxPool2D` --> `Flatten` --> `Dense 2`
    - Train Accuracy: `100%` 
    - Validation Accuracy: `65%` 

- Image classification using `VGG16` pre-trained model
    - Dataset: [Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats/data)
        - Taking only `1,200` images out of `50,000` to train.
    - Model: `VGG16`
        - `VGG16` - `last layer` --> `Dense 2`
    - Train Accuracy: `99.30%` 
    - Validation Accuracy: `96.50%` 

<p align="middle">
  <img src="sign language images.jpg" width="70%" />
</p>


- About `Mobile Net` for Image classificaiton
    - Shows how to prepare images to identify and classify
    - Model: Mobile Net

- Image classification using `Mobile Net` pre-trained model
    - Dataset: [Sign language digits](https://github.com/ardamavi/Sign-Language-Digits-Dataset)
    - Model: `Mobile Net`
        - `Mobile Net` - `last 4 layer` --> `Flaten` --> `Dense 10`
    - Train Accuracy: `99.80%` 
    - Validation Accuracy: `98.67%` 


## Prerequisites:
Below libraries are needed to execute this Python code.
- Python 3.9
- Tensorflow 2.8.0
- Keras 2.7.0
- Numpy
- Matplotlib

