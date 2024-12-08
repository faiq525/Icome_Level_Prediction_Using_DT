# Icome_Level_Prediction_Using_DT

This project aims to predict whether an individual's income exceeds $50,000 annually based on demographic and employment attributes. Using the Adult dataset, machine learning techniques, including Decision Trees, were applied to build and evaluate a predictive model.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Techniques Used](#techniques-used)
- [Project Structure](#project-structure)
- [Results](#results)
- [Applications](#applications)
- [License](#license)

## Overview
This project focuses on:
- Data preprocessing and exploratory data analysis.
- Identifying feature importance and optimizing the model based on top features.
- Building and evaluating a Decision Tree classifier.
- Hyperparameter tuning using GridSearchCV.
- Evaluating model performance using metrics like accuracy, confusion matrix, and classification report.

## Dataset
The dataset used is the [Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult) from the UCI Machine Learning Repository. It contains demographic and employment attributes of individuals, with the target variable indicating whether their income exceeds $50,000 annually.

## Techniques Used
- **Data Preprocessing**: Removal of irrelevant features and one-hot encoding of categorical variables.
- **Feature Importance Analysis**: Identifying the most important features using the Decision Tree model.
- **Machine Learning**: Decision Tree Classifier.
- **Hyperparameter Tuning**: GridSearchCV for optimal parameter selection.
- **Evaluation Metrics**: Accuracy score, confusion matrix, and classification report.

## Results
1. **Initial Model**: Trained the model on all features, achieving an accuracy of **85.03%**.
2. **Optimized Model**: Trained the model on only the top 5 most important features, achieving an accuracy of **84.95%**. This demonstrates that the model can achieve nearly the same accuracy with significantly fewer features, improving computational efficiency.

The top 5 features identified through feature importance were visualized and analyzed in the project.

## Applications
- **Credit Card Marketing**: Identifying potential customers for premium credit cards.
- **Insurance Planning**: Targeting individuals with higher income for premium plans.
- **Retail**: Designing personalized offers for high-income customers.
- **Recruitment**: Assisting workforce planning teams in identifying high-income professionals.

## License
This project is licensed under the MIT License
