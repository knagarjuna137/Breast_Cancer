# Breast_Cancer

Breast Cancer Detection Using CNN 
Breast cancer is the most commonly occurring cancer in women and the second most common cancer overall. There were over 2 million new cases in 2018, making it a significant health problem in present days.

The key challenge in breast cancer detection is to classify tumors as malignant or benign. Malignant refers to cancer cells that can invade and kill nearby tissue and spread to other parts of your body. Unlike cancerous tumor(malignant), Benign does not spread to other parts of the body and is safe somehow. Deep neural network techniques can be used to improve the accuracy of early diagnosis significantly.

Deep Learning is a subfield of machine learning concerned with algorithms inspired by the structure and function of the brain called an artificial neural network.

A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other. The pre-processing required in a ConvNet is much lower as compared to other classification algorithms.

What is Dropout
Dropout is a technique where randomly selected neurons are ignored during training. They are “dropped-out” randomly. This means that their contribution to the activation of downstream neurons is temporally removed on the forward pass and any weight updates are not applied to the neuron on the backward pass.

What is Batch Normalization
It is a technique which is designed to automatically standardize the inputs to a layer in a deep learning neural network.
e.g. We have four features having different unit after applying batch normalization it comes in similar unit.
By Normalizing the output of neurons the activation function will only receive inputs close to zero.
Batch normalization ensures a non vanishing gradient.



Importing necessary library that will use in model building.

<a><P>import tensorflow as tf

from tensorflow import keras

from tensorflow.keras import Sequential

from tensorflow.keras.layers import Flatten, Dense, Dropout, BatchNormalization

from tensorflow.keras.layers import Conv1D, MaxPool1D

from tensorflow.keras.optimizers import Adam</a></p>


print(tf.__version__)
2.3.0



pandas for loading and manipulating the data.

NumPy is used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform and matrices.

pyplot from matplotlib is used to visualize the results.

Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.



