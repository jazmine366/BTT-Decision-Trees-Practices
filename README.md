# Decision Tree Hyperparameter Tuning & Feature Importance

## Overview
This notebook explores Decision Tree classification using the Cell2Cell customer churn dataset. The project focuses on tuning decision tree hyperparameters, evaluating model performance, and analyzing feature importance to better understand which features contribute most to customer churn predictions.

---

## What I Did
- Loaded and explored the Cell2Cell customer churn dataset
- Handled missing values
- Encoded categorical features using one-hot encoding
- Split the data into training and testing sets
- Trained Decision Tree classifiers using **entropy** as the splitting criterion
- Compared model performance across different **max_depth** values
- Evaluated model accuracy on the test set
- Extracted feature importance scores using `model.feature_importances_`
- Ranked features by importance
- Visualized the top 10 most important features using Matplotlib

---

## Concepts Practiced
- Decision Trees
- Entropy & Information Gain
- Hyperparameter Tuning
  - `max_depth`
  - `min_samples_leaf`
- Feature Importance
- One-Hot Encoding
- Handling Missing Values
- Train/Test Split
- Model Evaluation (Accuracy)
- Data Visualization

---

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Key Takeaways
- Decision tree performance is strongly influenced by hyperparameter selection.
- Increasing tree depth can improve accuracy but may also increase the risk of overfitting.
- Feature importance scores help identify the variables that contribute most to model predictions.
- Comparing multiple models helps select more effective hyperparameter values.
- Visualizing feature importance makes decision tree models easier to interpret.
