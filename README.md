# Face Recognition with Convolutional Neural Networks

## Introduction

This project uses a convolutional neural network (CNN) built in Keras to perform facial recognition on the Labeled Faces in the Wild (LFW) dataset from scikit-learn. The goal is to accurately identify different celebrities based on photographs of their faces.

## Contents

The Jupyter notebook:

- Imports the LFW dataset
- Splits data into train and test sets 
- Defines CNN architecture with convolution, pooling, dropout and dense layers
- Compiles and trains model
- Makes predictions on test set
- Evaluates model accuracy 
- Visualizes some predictions

It also shows the full CNN architecture visualization produced by VisualKeras.

## Setup

To run this facial recognition project, you need:

- Python 3
- TensorFlow 
- Keras
- scikit-learn
- VisualKeras
- Open CV

Install requirements with:

```
pip install tensorflow keras scikit-learn visualkeras opencv-python
```

## Usage 

Run the Jupyter notebook cell-by-cell to execute the CNN facial recognition workflow from end-to-end.

## Results

The CNN model achieves an accuracy of 95% on the test set for recognizing individual identities. The final classification report and confusion matrix evaluate performance in detail.

## Customization

The CNN architecture and training hyperparameters can be tweaked as needed to experiment with improving accuracy. More data augmentation could also help the model generalize better to new faces.
