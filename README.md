# Bank Marketing Data - A Decision Tree Approach

## Project Description

This project aims to predict whether a client will subscribe to a term deposit based on demographic and behavioral data. We use the Bank Marketing dataset from the UCI Machine Learning Repository and build a classification model using a Decision Tree.

## Dataset

The dataset used in this project is the Bank Marketing dataset from the UCI Machine Learning Repository. It contains various attributes such as age, job, marital status, education, balance, and the target variable indicating whether the client subscribed to a term deposit.

## Project Structure

- `data/` - Directory to store the dataset
- `notebooks/` - Jupyter notebooks containing the code
  - `bank-marketing-data-a-decision-tree-approach.ipynb` - Original notebook
  - `bank-marketing-data-a-decision-tree-approach-updated.ipynb` - Updated notebook with decision tree classifie

## Prerequisites

Ensure you have the following installed:

- Python 3.x
- Jupyter Notebook

## Code Explanation
Data Preprocessing
Load the dataset
Create a binary column deposit_yes indicating whether the client subscribed to a term deposit
Encode categorical variables
Split the data into training and testing sets
Model Building
Train a Decision Tree classifier on the training data
## Evaluation
Predict on the test set
Evaluate the model's performance using accuracy, classification report, and confusion matrix
Visualization
Visualize the trained Decision Tree
## Results
The trained Decision Tree classifier is evaluated on the test set, and its performance is measured using various metrics. The tree is also visualized to understand the decision-making process.

## Contributing
If you would like to contribute to this project, please create a pull request or open an issue to discuss your changes.
