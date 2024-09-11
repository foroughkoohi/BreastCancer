# Breast Cancer Classification Project

## Project Overview
This project aims to classify breast cancer data using several machine learning algorithms. The dataset was obtained from the `sklearn` library, and the goal is to model and compare the performance of different classifiers.

## Dataset
- **Source**: `sklearn.datasets`
- **Test Size**: 20% of the dataset (`test_size=0.2`)

## Algorithms Used
The following algorithms were implemented and evaluated:
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Logistic Regression
- Artificial Neural Network (ANN)

## Evaluation Metrics
The models were evaluated based on the following metrics:
- **Accuracy**: Calculated for both training and test sets.
- **Precision & Recall**: Evaluated on the test set.

## Comparison and Visualization
All algorithms were compared for accuracy, precision, and recall. The results are presented using the following charts:

1. **Accuracy Score for Training Data**
   ![Train Accuracy Comparison](images/acc_train.png)

2. **Accuracy Score for Test Data**
   ![Test Accuracy Comparison](images/acc_test.png)

3. **Precision for Test Data**
   ![Precision Comparison](images/p_test.png)

4. **Recall for Test Data**
   ![Recall Comparison](images/r_test.png)


