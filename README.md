# Understanding Income Inequality with Machine Learning

## Introduction

This project explores income inequality in the United States using machine learning techniques. We aim to predict income levels among US citizens based on various demographic and socioeconomic factors. The analysis includes data preprocessing, exploratory data analysis (EDA), modeling using the K-nearest neighbors (KNN) algorithm, and evaluation of model performance.

## Problem Statement

Income inequality is a pressing issue globally, with significant implications for economic stability and social welfare. By constructing predictive models to classify individuals into low-income and high-income categories, we seek to gain insights into the factors driving income disparities and inform policy interventions for greater financial equity.

## Data

We utilize a dataset sourced from the 1994 Census database, containing information on demographic attributes such as age, education, occupation, and marital status, among others. The target variable 'income' indicates whether an individual earns more than $50,000 annually ('>50K') or not ('<=50K').

## Methodology

### Data Preprocessing and Transformation
- Handling missing values and outliers
- Encoding categorical variables
- Feature scaling for numerical attributes

### Exploratory Data Analysis (EDA)
- Visualizing income distribution
- Analyzing relationships between income and demographic factors
- Identifying key insights into income disparities

### Modeling
- Implementing K-nearest neighbors (KNN) classification algorithm
- Tuning hyperparameters and evaluating model performance
- Comparing accuracy, precision, recall, and F1 score for different K values

## Conclusion

The analysis reveals important insights into income inequality in the United States. Factors such as education, occupation, and marital status significantly influence income levels. The KNN model, with an optimal K value of 20, demonstrates robust performance in classifying individuals based on income.

## Recommendations

Based on our findings, policymakers and stakeholders can:
- Prioritize education and vocational training programs to enhance earning potential
- Implement targeted policies to support individuals in low-income occupations
- Promote initiatives for financial literacy and empowerment

## References

- Scikit-learn: Machine Learning in Python
- Scikit-learn Documentation: Cross-validation
- IBM: What is the k-nearest neighbors algorithm?
- GeeksforGeeks: K-Nearest Neighbor (KNN) algorithm


Feel free to reach out with any questions or suggestions!
