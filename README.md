# Pumpkin Seeds Classification with Support Vector Machines

## Project Description:

This project focuses on the classification of pumpkin seeds using Support Vector Machines (SVMs), a powerful machine learning technique. The goal is to accurately categorize pumpkin seeds based on various physical attributes and shapes. The project encompasses data preprocessing, SVM model building, and visualization of decision boundaries.

## Components:

Data Loading and Exploration:

The project starts by loading a dataset containing features of pumpkin seeds, such as area, major axis length, eccentricity, and more.
Data exploration techniques are employed to understand the dataset's structure and characteristics.
Data Preprocessing:

Data preprocessing steps include handling missing values, label encoding the target variable, and standardizing the feature values using the StandardScaler.
SVM Model Building:

Three different SVM models are implemented with different kernel functions:
Radial Basis Function (RBF) Kernel
Polynomial Kernel
Sigmoid Kernel
Each SVM model is trained on the preprocessed data to classify pumpkin seeds into distinct categories.
Model Evaluation:

Model evaluation metrics such as precision, recall, F1-score, and confusion matrices are used to assess the performance of each SVM model.
Visualization of confusion matrices using heatmaps provides a clear understanding of the model's classification performance.
Principal Component Analysis (PCA):

Principal Component Analysis (PCA) is applied to reduce the dimensionality of the dataset while preserving its variance.
Reduced-dimension data is used to visualize the decision boundaries of the SVM models.
Visualization of Decision Boundaries:

Decision boundary plots are generated to visualize how each SVM model separates different classes of pumpkin seeds in the reduced feature space.
These plots provide insights into the classification capabilities of each SVM kernel function.

## Results:

Three SVM models with different kernel functions (RBF, Polynomial, Sigmoid) are trained and evaluated for pumpkin seed classification.
Model evaluation metrics and decision boundary visualizations are provided to understand each model's strengths and weaknesses.
The project showcases the power of SVMs in handling classification tasks for complex datasets.
