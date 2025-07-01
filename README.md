## Project Aim
Build and evaluate classification models to recommend Megaline's legacy plan users a newer plan based on their usage behavior.

## Tools Used
- Python

- pandas, NumPy

- scikit-learn

- matplotlib, seaborn

## Results
# Decision Tree (depth=3):
- Validation Accuracy: 79.2%

- Test Accuracy: 80.6%

- Best performance overall

# Random Forest (n=4):

- Validation: 79.2%
-  Test: 80.1%

- Very close to Decision Tree in performance

# Logistic Regression:

- Accuracy: 70.8% (validation & test)

- Failed to meet the 75% threshold

Final Recommendation: Deploy the Decision Tree model due to slightly higher generalization on unseen data.
