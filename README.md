# Firm-Collapse-Prediction


## Overview

This project aims to predict company bankruptcy using various machine learning algorithms. The project was completed as part of the MGMT 571 course and achieved a rank of #4.

## Team Members
- Piyush Kakde
- Pratik Mahesh Merchant
- Priyam Sarkar

## Table of Contents
- [Overview](#overview)
- [Team Members](#team-members)
- [Project Structure](#project-structure)
- [Data](#data)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Preprocessing](#preprocessing)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Results](#results)
- [Key Takeaways](#key-takeaways)
- [Acknowledgements](#acknowledgements)

## Project Structure

- **Exploratory Data Analysis (EDA)**: Before and after preprocessing
- **Preprocessing**: Data filtering and replacement
- **Initial Approach**: Single data partition, 4 algorithms tested
- **Next Steps**: Ensemble method and multiple data partitions
- **Final Model**: Combination of various algorithms using ensemble techniques

## Data

### Training Data
- The training data should include features relevant to predicting company bankruptcy, such as operational efficiency, profitability, liquidity, and leverage ratios.

### Test Data
- The test data should follow the same format as the training data for consistency in preprocessing and prediction.

## Exploratory Data Analysis (EDA)

### Before Preprocessing
- Summary statistics and Chi-square tests to identify important features and relationships.

### After Preprocessing
- Analysis reveals that the likelihood of bankruptcy is closely linked to operational efficiency, profitability, liquidity, and leverage ratios.
- Addressed class imbalance in the dataset.

## Preprocessing

### Steps:
1. **Filter Property**: Remove irrelevant features.
2. **Replacement Property**: Handle missing values and outliers.

## Modeling

### Initial Approach
- Data partitioned into train (70%) and validation (30%) sets.
- Algorithms tested: Logistic Regression, Neural Network, Gradient Boosting, HP Neural Network.
- Initial models showed low accuracy and significant difference in ROC between training and validation sets.

### Ensemble Method
- Applied ensemble methods to improve predictive performance.
- Multiple data partitions were used to simulate cross-validation.

### Final Model
- Combined various algorithms using ensemble techniques.
- Compared models using ROC as the evaluation criteria.

## Evaluation

### Metrics
- **Receiver Operating Characteristic (ROC)**: Used for evaluating model performance, especially with imbalanced datasets.

## Results

### Final Model Performance
- Public Score: 0.95701
- Private Score: 0.95331

## Key Takeaways

- **ROC Curve**: Essential for evaluating models with imbalanced datasets.
- **Data Mixing**: Helps improve model performance when tested with new data.
- **Complex Patterns**: Neural Networks and Gradient Boosting work well with complex patterns and uneven distributions.
- **Simpler Methods**: Decision trees may not perform as well in these scenarios.

## Acknowledgements

- Thanks to the MGMT 571 course instructors and the open-source community for the tools and resources used in this project.
