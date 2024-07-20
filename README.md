# Rock vs Mine Prediction using Sonar Data

## Overview

This project aims to classify objects as either rocks or mines using sonar data. Various machine learning models were implemented to determine which model achieves the highest accuracy.

## Dataset

The dataset used is `Data_sonar.csv`, which contains sonar readings for objects. Each instance in the dataset has 60 attributes (sonar readings) and a class label indicating whether the object is a rock or a mine.

## Models Implemented

1. **Logistic Regression**
   - File: `1_logistic_regression.py`
   - Description: A logistic regression model was trained to classify the objects. Logistic regression is a linear model used for binary classification problems.

2. **K-Nearest Neighbors (KNN)**
   - File: `2_k_nearest_neighbors.py`
   - Description: The KNN algorithm was used to classify the objects based on their nearest neighbors. KNN is a non-parametric method used for classification and regression.

3. **Support Vector Machine (SVM)**
   - File: `3_kernel_svm.py`
   - Description: A kernel SVM model was implemented. SVM is a powerful classification method that finds the hyperplane that best separates the classes in the feature space.

4. **Naive Bayes**
   - File: `4_naive_bayes.py`
   - Description: A Naive Bayes classifier was used. Naive Bayes is a probabilistic classifier based on applying Bayes' theorem with strong independence assumptions between the features.

5. **Decision Tree**
   - File: `5_decision_tree_classification.py`
   - Description: A decision tree classifier was implemented. Decision trees are non-linear models that split the data into subsets based on the value of input features.

6. **Random Forest**
   - File: `6_random_forest_classification.py`
   - Description: A random forest classifier, which is an ensemble method using multiple decision trees, was implemented. It improves the classification accuracy by combining the predictions of several base estimators.

7. **Support Vector Machine (Linear)**
   - File: `7_support_vector_machine.py`
   - Description: A linear SVM model was implemented. SVM is effective in high-dimensional spaces and for cases where the number of dimensions is greater than the number of samples.

## Evaluation

Each model was evaluated based on its accuracy. The goal was to determine which model performs best in predicting whether an object is a rock or a mine.

## Results

The model with the highest accuracy was selected as the final model. Detailed results and comparisons of the models' performance can be found in the individual script files.

## Conclusion

By implementing and comparing various machine learning models, the best-performing model for classifying objects as rocks or mines using sonar data was identified. This approach ensures that the most accurate and reliable model is used for predictions.

## Usage

To run any of the models, execute the corresponding Python script. For example, to run the logistic regression model, use the following command:

```bash
python 1_logistic_regression.py
