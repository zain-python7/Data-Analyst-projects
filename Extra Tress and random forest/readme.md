# Random Forest vs Extra Trees

## Overview

This project compares **Random Forest Classifier** and **Extra Tress Classifier** on a synthetic dataset using Python and Scikit-learn.

## Dataset

The dataset contains three columns:

* `Age`
* `Income`
* `Churn` (target variable: 0 or 1)

The dataset has a clear relationship between Age, Income, and Churn, making the classification task relatively easy.

## Results

| Model         | Test Accuracy | Mean CV Accuracy |
| ------------- | ------------: | ---------------: |
| Random Forest |          100% |             100% |
| Extra Trees   |          100% |             100% |

Both models achieved perfect accuracy on the test set and across 5-fold cross-validation.

## Key Observations

* Both models performed equally well on this dataset.
* Cross-validation showed consistent performance across all five folds.
* The strong separation between the classes explains why the task is relatively easy.

## Technologies

* Python
* Pandas
* Scikit-learn

## Conclusion

Both classifiers achieved 100% accuracy on this synthetic dataset. However, these results should not be generalized to real-world data because the target is unusually easy to predict from the features.
