# Image Classification using CNN and pre-trained models
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)

## Description:
This repository includes:
- Sequential model 
    - Shows how to model a Deep NN with steps:
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
        - `Conv2D` \to MaxPool2D \to `Conv2D` \to MaxPool2D \to Flatten \to Dense 
    - Train Accuracy: `100%` 
    - Validation Accuracy: `65%` 

- Image classification using VGG16
    - Dataset: [Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats/data)
        - Taking only `1,200` images out of `50,000` to train.
    - Model: VGG16
        - `Conv2D` \to MaxPool2D \to `Conv2D` \to MaxPool2D \to Flatten \to Dense 
    - Train Accuracy: `100%` 
    - Validation Accuracy: `65%` 

