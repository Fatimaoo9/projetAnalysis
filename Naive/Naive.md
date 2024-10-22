# Project 1
#  Iris Dataset Classification

## Description
The Iris dataset is a well-known dataset used in machine learning and data classification. It contains information about iris flowers, consisting of 150 samples divided into three main classes:

1. Iris-setosa
2. Iris-versicolor
3. Iris-virginica

### Features:
- sepal_length: Length of the sepal (in millimeters).
- sepal_width: Width of the sepal (in millimeters).
- petal_length: Length of the petal (in millimeters).
- petal_width: Width of the petal (in millimeters).

### Target:
- class: Type of the flower.

### Statistics:
- Contains 150 rows and 5 columns.
- All values are present, with no missing data.

### Uses:
This dataset is used to develop classification models and evaluate algorithm performance, making it ideal for machine learning.

## Libraries Used

1. Pandas: A data analysis library used for loading and processing data in the form of DataFrames.
   - Function: Reading, exploring, and preparing data for analysis.

2. Scikit-learn: A machine learning library used for splitting data, training models, and evaluating their performance.
   - Functions:
     - train_test_split: Splitting data into training and testing sets.
     - GaussianNB: Implementing the Gaussian Naive Bayes model.
     - accuracy_score and classification_report: Evaluating model performance.

3. Matplotlib: A data visualization library used for creating charts and graphs.
   - Function: Visualizing results to better understand performance.
