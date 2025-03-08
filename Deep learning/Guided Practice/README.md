Guided Session 1 : CNN practice 

Practice Description: Pneumonia Detection Using Chest X-Ray Images
Objective:
The goal of this practice is to build an image classification pipeline to detect whether a patient has pneumonia or is healthy based on chest X-ray images. The task involves experimenting with multiple approaches to identify the most effective method for this medical imaging problem.



Dataset: Chest X-Ray Images for Pneumonia
Link: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
Details: The dataset contains labeled chest X-rays categorized into two classes:
Normal: Healthy X-rays.
Pneumonia: X-rays showing signs of pneumonia.
Data Split: Train, Validation, and Test sets are pre-separated.

Task:
Train a classification model to predict whether an input chest X-ray shows signs of pneumonia (binary classification: Pneumonia or Normal).



Steps:

1. Build a CNN from Scratch
Objective: Develop a custom Convolutional Neural Network (CNN) architecture tailored for the dataset.
Steps:
Design a CNN architecture with layers like Conv2D, MaxPooling2D, Dropout, and Dense.
Use techniques like:
Data augmentation (e.g., rotation, flipping, zooming).
Regularization (dropout, weight decay).
Early stopping for training stability.
Train the network from scratch on the dataset.Evaluation: Compare training/validation accuracy and analyze performance using metrics like precision, recall, F1-score, and AUC.

2. Use a Famous CNN Architecture
Objective: Leverage a popular, proven CNN architecture like VGG16, ResNet-50, or EfficientNet.
Steps:
Load the pre-defined architecture from torchvision.models.
Randomly initialize weights instead of using pre-trained weights.
Fine-tune the network for the binary classification task.
Optimize hyperparameters like learning rate, optimizer type, and batch size.
Evaluation: Compare results against the custom CNN and evaluate the impact of a deeper, more standardized architecture

3. Transfer Learning
Objective: Use a pre-trained model to leverage features learned on large datasets like ImageNet.
Steps:
Choose a pre-trained model (e.g., ResNet-50, DenseNet, Inception).
Replace the final fully connected layer with a binary classification head.
Freeze some earlier layers to retain pre-learned features.
Fine-tune the remaining layers on the Chest X-Ray dataset.
Experiment with fully fine-tuning the entire model.
Evaluation: Analyze performance improvements compared to training from scratch.

Experimentation Goals:

1. Compare performance across all three methods:

* Custom CNN
* Standard Architecture (from scratch)
* Transfer Learning

2. Use metrics like:
* Accuracy
* Precision, Recall, and F1-score
* ROC-AUC for assessing model confidence.

