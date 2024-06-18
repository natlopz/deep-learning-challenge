# deep-learning-challenge
Module 21 Challenge

Please check Neural Network Model document for a detailed report.

# Neural Network Model

## Overview:
This analysis aims to preprocess a dataset of charity applications and develop a deep neural network model to predict their success. By refining the preprocessing steps and optimizing the neural network architecture, we strive to achieve a model accuracy of 75% or higher in forecasting the success of charity applications.

## Results:
Model Performance:

•	Accuracy Achieved: 72.84%

•	Target Accuracy: 75% or above

•	Optimization Techniques Used: Batch Normalization, Dropout, and Hyperparameter Tuning.


![image](https://github.com/natlopz/deep-learning-challenge/assets/152227662/94421cbd-750d-42c6-9ae9-ce97f9228dc1)

Model Architecture and Performance:

•	Input Layer: 512 neurons, ReLU activation

•	Hidden Layers: 256, 128, 64, and 32 neurons with ReLU activation

•	Output Layer: 1 neuron, Sigmoid activation

![image](https://github.com/natlopz/deep-learning-challenge/assets/152227662/bacac92e-48de-4f48-9804-c234406b1705)

## Summary:
The deep learning model to predict the success of charity applications reached an accuracy of about 72-73%, which is just below the 75% goal. Even after trying batch normalization, dropout, and fine-tuning, the performance wasn't quite there. To get better results, using methods like Random Forest or Gradient Boosting could help. These techniques can manage complex data, reduce overfitting, and show which features are most important. With proper data preparation and tuning, these models might hit the accuracy target. Switching to these ensemble methods could make the predictions more accurate and reliable.
