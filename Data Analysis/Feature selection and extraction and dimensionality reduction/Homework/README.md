## Dimensionality Reduction Homework

This homework focuses on applying dimensionality reduction techniques to the MNIST dataset and evaluating the performance of each method in the context of a classification task using a K-Nearest Neighbors (KNN) classifier.

## Instructions

## Step 1: Data Preparation
Download the MNIST dataset from this link and save it as a numpy array.
The dataset consists of 60,000 training images and 10,000 testing images of handwritten digits (0-9).
Load the data into Python using the numpy library.
Split the dataset into training and testing sets using an 80:20 ratio.

## Step 2: Dimensionality Reduction
Apply the following dimensionality reduction techniques to the training set:

Principal Component Analysis (PCA)
t-Distributed Stochastic Neighbor Embedding (t-SNE)
Linear Discriminant Analysis (LDA)
Singular Value Decomposition (SVD)
For each technique:

Reduce the dimensions of the data.
Visualize the reduced data using a scatter plot where each point is colored according to its digit label.

## Step 3: Classification
Train a K-Nearest Neighbors (KNN) classifier with K = 5 on the reduced training data.
Evaluate the performance of the classifier on the reduced testing data.
Compare the classification performance of each dimensionality reduction technique based on:
Classification accuracy
Time taken to train the classifier

## Usage

## Clone this repository to your local machine:

git clone https://github.com/disilakarl/dimensionality-reduction-homework.git
Follow the steps in the Jupyter notebook to complete the homework.

Run the provided code cells to download the dataset, apply dimensionality reduction techniques, and train the KNN classifier.

Visualize the results and analyze the classification performance based on accuracy and training time.

## Dependencies
Ensure that the following libraries are installed to run the notebook: 

      numpy
      matplotlib
      seaborn
      scikit-learn
      pandas
      
You can install them using pip:

      pip install numpy matplotlib seaborn scikit-learn pandas

## Contact
For any questions or feedback, feel free to reach out:

Email: disila.karl@hotmail.com
LinkedIn: Disila Karl William
