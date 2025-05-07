# ML_Space_Classification

## Overview
This project classifies celestial objects (galaxies, stars, and quasars) based on data from the Sloan Digital Sky Survey (SDSS). Using machine learning techniques, specifically **Logistic Regression** and **K-Nearest Neighbors (KNN)**, the goal is to predict whether a given object is a galaxy, star, or quasar based on its photometric features.

## Problem Statement
The classification of cosmic objects is vital to astrophysics. Given a dataset from SDSS, this project classifies objects into three categories: **galaxies**, **stars**, or **quasars**. With 100,000 samples and 42 features, the task is to apply supervised learning to predict the correct class.

## Data
The dataset used for this project is from the **Sloan Digital Sky Survey** and contains:
- **100,000 samples** with **42 features** each.
- The features include photometric data across various wavelengths (e.g., red, green, ultraviolet).
- The target classes are **galaxies**, **stars**, and **quasars**.

### Tools & Libraries:
- `pandas`: Data manipulation.
- `scikit-learn`: For model training, evaluation, and scaling.
- `matplotlib`: For visualizing results.

## Methods

### Logistic Regression
Logistic Regression is used for multiclass classification with a softmax activation function. It's effective when the classes are linearly separable. However, its performance might drop in cases with more complex, non-linear boundaries.

### K-Nearest Neighbors (KNN)
KNN classifies objects based on the majority class of their nearest neighbors. It's well-suited for non-linear decision boundaries but is computationally expensive due to the need to evaluate all training samples for each prediction.

## Results

### Model Performance
- **Logistic Regression** achieved **98-99% accuracy** across training, validation, and testing.
- **K-Nearest Neighbors** performed slightly worse with **97-98% accuracy**.

## Conclusion
Both **Logistic Regression** and **K-Nearest Neighbors** performed well in classifying cosmic objects. While **Logistic Regression** had a slight edge in terms of accuracy and computational efficiency, **KNN** could potentially outperform Logistic Regression in situations with more complex, non-linear data. This project provided hands-on experience with classification models and allowed me to explore machine learning in an astrophysics context.