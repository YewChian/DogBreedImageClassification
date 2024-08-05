# Dog Breed Image Classification
Deep convolutional neural network classification of dog breeds with a model pre-trained on cat and dog image classification.

## Introduction
A few experiments were conducted to observe the different approaches of transfer learning in a convolutional neural network. The datasets used were the Stanford Dogs dataset, and the Kaggle cats and dogs dataset.

## Background
Transfer learning refers to using pre-trained weights, usually from models trained on a similar dataset, to train a model on a new problem. In these experiments, we vary the amount of pre-trained weights used from the base model and observe the results.

The base model here refers to a convolutional neural network that has been trained on the Stanford Dogs dataset, which is used to classify between dog breeds. The new problem is to classify between cats and dogs, which is a binary classification problem instead, hence the need to replace the output layer of the base model.

## Discussion
Refer to report.
