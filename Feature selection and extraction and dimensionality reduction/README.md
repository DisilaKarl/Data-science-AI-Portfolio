Step 1: Data Preparation
Download the MNIST dataset from https://www.kaggle.com/datasets/hojjatk/mnist-dataset and save it as a numpy array. The dataset consists of 60,000 training images and 10,000 testing images of handwritten digits from 0 to 9.
Load the data into Python using the numpy library.
Split the data into a training set and a testing set, with a 80:20 split ratio.

Step 2: Dimensionality Reduction
Apply each of the following dimensionality reduction techniques to the training set: PCA, t-SNE, LDA, SVD
Visualize the reduced data using a scatter plot, with different colors representing different digit labels.

Step 3: Classification
Train a K-Nearest Neighbors (KNN) classifier on the reduced training data, with K = 5.
Evaluate the performance of the classifier on the reduced testing data.
Compare the classification performance of each dimensionality reduction technique, based on the classification accuracy and the time taken to train the classifier.
