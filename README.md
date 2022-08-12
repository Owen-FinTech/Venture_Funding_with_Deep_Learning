# Venture_Funding_with_Deep_Learning

## Overview
In this project I create a deep learning model that predicts whether startups will be successful if funded by a venture capital firm. This consists of three technical stages:

* Preprocessing data for a neural network model.

* Use the model-fit-predict pattern to compile and evaluate a binary classification model.

* Optimising the model.

## Technologies
Running the Jupyter Notebook file requires installation of the Pandas, Tensor Flow, Keras and SciKit Learn modules and libraries for Python.

## Results

Three models were created but they yielded very similar results: 

* The Original Model had 2 hidden layers of 58 and 29 neurons and resulted in a loss of 0.564 and an accuracy of 0.729 over 50 epochs.

* Alternative Model 1 had the same amount of neurons as the original model but also included a dropout layer and regularization which resulted in a loss of 0.561 and an accuracy of 0.731 over 50 epochs.

* Alternative Model 2 had 3 hidden layers of 78, 52 and 34 neurons and used the Scaled Exponential Linear Unit (SELU) activation function. It resulted in a loss of 0.587 and an accuracy of 0.732 over 200 epochs.

## Contributors

Owen Harris. 
