# Decision Tree Feature Importance

## Overview

This notebook explores feature importance using a Decision Tree classifier on the Cell2Cell customer churn dataset. It also examines how different decision tree hyperparameters affect model performance.

## What I Did

- Loaded and prepared the dataset
- Split the data into training and testing sets
- Trained Decision Tree classifiers using entropy as the split criterion
- Compared model accuracy for different `max_depth` values
- Retrieved feature importance scores using `model.feature_importances_`
- Sorted features by importance
- Visualized the top 10 most important features with a bar chart

## Concepts Practiced

- Decision Trees
- Entropy and Information Gain
- Hyperparameter tuning (`max_depth`, `min_samples_leaf`)
- Feature importance
- Train/test split
- Model evaluation using accuracy
- Data visualization with Matplotlib

## Libraries Used

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Key Takeaways

- Decision tree performance changes with tree depth.
- Feature importance identifies which features contribute most to predictions.
- Increasing tree depth can lead to overfitting if not controlled.
- Visualizing feature importance makes it easier to interpret the model.
- Calculating entropy and information gain by hand
