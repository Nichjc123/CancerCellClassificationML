# CRC Histology Cell Classification (ML)

### Summary

This repo contains a python deep learning project. I've created a neural network to classify images from the colorectal histology dataset with 92.13% accuracy over testing data.

### Data

The dataset used in this project is a tensorflow dataset named [colorectal_histology](). This dataset contains images of various tissue structures of different sizes containing cancer cells.

### Objective

The goal of this immage classification task is to aid pathologists in the study of colorectal cancer (CRC),along with it's degree of depth/presence in various tissue structures.

### Model development

This model was developed and optimized over hundreds of iterations. Modifications to model depth, width and hyperparameters were key in achieving the end result.

The final model is quite shallow, the convulotional base of the model contains four max pooling and covolutional layers, and 3 densely connected classifier layers.

### Results

The trained model achieved a sparse categorical accuracy of **92.13%** over the training data.

_Here are graphs of the model's training cycle:_

![training and validation accuracy](/imgClass1.png)

![training and validation loss](/imgClass2.png)
