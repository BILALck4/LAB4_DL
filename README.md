# Lab 1 Report

## Objective:
The main goal of this lab was to develop proficiency in using the PyTorch library for both Classification and Regression tasks, employing Deep Neural Network (DNN) and Multi-Layer Perceptron (MLP) architectures.

## Table of Contents
- [Part One: Regression](#part-one-regression)
- [Part Two: Multi-Class Classification](#part-two-multi-class-classification)
- [Conclusion](#conclusion)

## Part One: Regression

### Dataset:
- [NYSE Stock Prices](https://www.kaggle.com/datasets/dgawlik/nyse)

### Work Completed:
1. **Exploratory Data Analysis (EDA):**
    - Conducted comprehensive EDA techniques to understand and visualize the dataset, gaining insights into key features and distributions.

2. **Deep Neural Network Architecture:**
    - Implemented a DNN architecture using PyTorch for the regression task, incorporating relevant features from the dataset.

3. **Hyperparameter Tuning with GridSearch:**
    - Utilized GridSearch from the sklearn library to identify the best hyperparameters, such as learning rate, optimizers, epochs, and model architecture, improving the efficiency of the model.

4. **Visualization:**
    - Generated graphs illustrating Loss vs. Epochs and Accuracy vs. Epochs for both training and test data.
    - Provided interpretations of the observed trends in the visualizations.

5. **Regularization Techniques:**
    - Applied various regularization techniques to the architecture.
    - Compared the results obtained with the initial, non-regularized model.

## Part Two: Multi-Class Classification

### Dataset:
- [Machine Predictive Maintenance](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)

### Work Completed:
1. **Data Preprocessing:**
    - Applied preprocessing techniques to clean and standardize/normalize the data.
    - Encoded categorical variables and ensured the dataset was ready for analysis.

2. **Exploratory Data Analysis (EDA):**
    - Conducted EDA to understand the dataset, highlighting key patterns and characteristics.

3. **Data Augmentation:**
    - Applied data augmentation techniques to balance the dataset, addressing potential class imbalances.

4. **Deep Neural Network Architecture:**
    - Developed a PyTorch-based DNN architecture to handle the multi-class classification task, considering the unique characteristics of the dataset.

5. **Hyperparameter Tuning with GridSearch:**
    - Leveraged GridSearch to identify optimal hyperparameters, enhancing model efficiency.

6. **Visualization:**
    - Visualized Loss vs. Epochs and Accuracy vs. Epochs for both training and test data.
    - Provided interpretations based on the observed trends.

7. **Metrics Calculation:**
    - Calculated key metrics such as accuracy, sensitivity, and F1 score on both training and test datasets.

8. **Regularization Techniques:**
    - Applied various regularization techniques to the architecture.
    - Compared the results with the initial, non-regularized model.

## Conclusion:
This lab provided valuable hands-on experience in using PyTorch for diverse tasks, emphasizing the significance of exploratory data analysis, hyperparameter tuning, and model evaluation techniques. The comparison of results before and after regularization highlighted the impact of these techniques on model performance.
