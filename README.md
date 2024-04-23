# Comparative Study of MLP and SVM in Musical Genre Classification
This project investigates the application of advanced neural computing models, specifically Multilayer Perceptron (MLP) and Support Vector Machines (SVM), for the classification of musical genres. The study leverages a dataset from Kaggle, which includes musical features of songs to categorize them into various genres.

## Overview
The primary aim of this project is to analyze and compare the efficacy of MLP and SVM in classifying music genres based on their characteristics. These models were chosen due to their robustness in handling complex datasets and their ability to discern intricate patterns in data.

## Project Details
Dataset: The dataset consists of 50,005 entries with 16 attributes, each describing unique musical traits of songs. The dataset is well-balanced across ten musical genres, which facilitated a straightforward modeling process without the need for data balancing techniques.
Preprocessing: Data cleansing involved removing duplicates and records with null values. Four features were discarded as irrelevant, and the remaining data was normalized and encoded as required for model input.

## Models Used:
Multilayer Perceptron (MLP): Implemented using PyTorch, this model utilized a 3-layer architecture with ReLU activation and dropout to prevent overfitting.
Support Vector Machine (SVM): Implemented using Scikit-learn, the SVM model used an RBF kernel initially, with hyperparameters optimized through GridSearchCV and Optuna.

## Key Findings
- MLP Model: The optimized MLP model demonstrated a final accuracy of approximately 59%, showcasing its capability to capture complex nonlinear relationships in the data.
- SVM Model: The SVM model, after extensive hyperparameter tuning, reached an accuracy of about 57.69%. It proved effective in defining precise classification margins even in a high-dimensional feature space.

## Conclusion
Both models showed close performance metrics in classifying music genres. However, the SVM model edged out slightly in terms of handling high dimensionality with less computational effort and time, making it slightly more suitable for this task.

## Future Work
Further improvements could involve exploring more complex neural network architectures for MLP and experimenting with different kernel functions for SVM to enhance the models' accuracy and efficiency.

