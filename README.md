# Support-Vector-Machines-SVMs-for-Skin-Cancer-Classification

Project Abstract :-

This project aims to develop and compare two machine learning models, an
Artificial Neural Network (ANN) and a Support Vector Machine (SVM), for
classifying skin cancer images. The models are trained and evaluated on a dataset
of skin cancer images, and their performance is compared using metrics such as
accuracy and cross-validation scores.

Introduction :-

skin cancer is a significant public health concern, and early detection is crucial for
effective treatment. Machine learning algorithms can be used to analyze skin
cancer images and aid in diagnosis. This project explores the use of two machine
learning models, ANN and SVM, for classifying skin cancer images.

Description of the Project :-

The project involves loading a dataset of skin cancer images from two CSV files,
one for training and one for testing. The data is preprocessed using PyTorch's
transforms module and Scikit-learn's StandardScaler. The ANN model is defined
using PyTorch, with three fully connected layers, and the SVM model is defined
using Scikit-learn. The models are trained and evaluated on the dataset, with the
SVM model undergoing cross-validation to assess its performance.

Algorithm and Methodologies :-

The algorithms used in this project are:
Artificial Neural Network (ANN): A feedforward neural network with
three fully connected layers, using the ReLU activation function and
cross-entropy loss.
Support Vector Machine (SVM): A linear SVM with a regularization
parameter of 1.
