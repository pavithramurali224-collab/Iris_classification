# Iris_classification
This document provides a complete explanation of the Python code used to load, analyze, visualize, train, and evaluate a Logistic Regression model on the Iris dataset.

Google Colab Notebook Link
Access the working notebook here:
https://colab.research.google.com/drive/1L34oU9HNCGDFKcCRiTAqAeOA9qYvLody?usp=sharing
1. Import Required Libraries
The script begins by importing necessary Python libraries:
- numpy and pandas for data handling
- seaborn and matplotlib for visualization
- sklearn for dataset loading, preprocessing, model training, and evaluation
2. Load the Dataset
The Iris dataset is loaded using sklearn's load_iris() function. Feature data is stored in variable X and target classes in y. Target numbers (0, 1, 2) are mapped to actual species names.
3. Exploratory Data Analysis (EDA)
Two main visualizations are generated:
- Pairplot: To observe feature relationships with species color coding.
- Correlation heatmap: To analyze numerical correlations between features.
4. Dataset Splitting & Preprocessing
The dataset is split into training (80%) and testing (20%) sets. StandardScaler is applied to standardize the feature values, improving model performance.
5. Train Logistic Regression Model
A Logistic Regression model is trained using the scaled training data. Predictions are then generated for the test set.
6. Model Evaluation
Evaluation metrics include:
- Confusion Matrix
- Classification Report (precision, recall, F1-score)
- Accuracy Score
