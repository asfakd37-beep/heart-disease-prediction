# heart-disease-prediction
This project builds machine learning and deep learning models to predict heart disease severity using the UCI Heart Disease dataset. The work includes data preprocessing, supervised learning with MLP, Random Forest, and 1D CNN models, plus unsupervised clustering for pattern discovery.

Project Overview
The dataset contains 920 patient records with 13 clinical features, including age, chest pain type, cholesterol, maximum heart rate, and other cardiac indicators. The target variable represents heart disease severity on a 5-class scale from 0 to 4. The notebook preprocesses the data, trains multiple models, compares performance, and visualizes key results.

Models Used
Multi-Layer Perceptron (MLP) for multi-class classification.

Random Forest as an ensemble learning baseline and interpretable model through feature importance.

1D Convolutional Neural Network (CNN) to test deep learning performance on reshaped tabular input.

K-Means Clustering for unsupervised grouping analysis.

Results Summary:
Model	Test Accuracy
MLP	53.26%
Random Forest	58.15%
1D CNN	43.48%
The Random Forest model achieved the best accuracy among the supervised models in this project.

Preprocessing Steps
Removed non-clinical identifier columns.

Imputed missing numerical values using the median.

Encoded categorical variables using label encoding.

Standardized features with StandardScaler.

Used stratified train-test splitting to preserve class distribution.

Applied class weights to reduce the effect of class imbalance during training.


Author
Coursework project on heart disease severity prediction using machine learning and deep learning.
