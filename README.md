Sonar Rock vs Mine Detection

This project leverages machine learning to distinguish between rocks and mines using sonar signals, which is crucial for the safety of submarines navigating potentially dangerous underwater environments.

Table of Contents

Overview
Dataset
Installation
Usage
Model Training and Evaluation


The primary objective of this project is to create a system that can classify sonar signals as either rocks (R) or mines (M). This is achieved using a logistic regression model trained on a dataset of sonar readings.

Dataset

The dataset comprises 208 samples, each with 60 features representing sonar readings. The 61st column contains the labels, indicating whether the sample is a rock or a mine.

Dataset Characteristics:

Samples: 208
Features: 60
Labels: Rock (R) or Mine (M)
The dataset is balanced, with 111 samples labeled as mines and 97 as rocks, ensuring an equitable distribution for training and testing the model.

Installation

Clone the repository from GitHub.
Navigate to the project directory.
Install the required dependencies using pip install.
Usage

Load the dataset into a pandas DataFrame.
Preprocess the data by separating features and labels.
Split the dataset into training and testing sets.
Model Training and Evaluation

Training the Model
The logistic regression model is trained using the training dataset. The model learns to classify sonar signals based on the patterns and characteristics found in the training data.

Evaluating the Model
The model's performance is evaluated using accuracy scores on both the training and testing datasets.

Model Performance:

Training Accuracy: ~83%
Testing Accuracy: ~76%
The slightly lower accuracy on the testing data is expected, as the model encounters unseen data, but it still demonstrates robust performance.
