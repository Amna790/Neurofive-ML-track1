# Neurofive-ML-track1
Machine Learning internship tasks and  EDA
# Neurofive-ML-track1

Machine Learning internship tasks and EDA

## Credit Card Fraud Detection - Handling Imbalanced Data

### Objective
This task focuses on handling imbalanced data using a Credit Card Fraud Detection dataset.

### Dataset
The dataset contains credit card transactions where:
- 0 = Normal transaction
- 1 = Fraudulent transaction

### Work Done
- Checked the class distribution
- Visualized class imbalance using a bar chart
- Trained a Logistic Regression baseline model
- Evaluated Precision, Recall, and F1-score
- Applied SMOTE to handle class imbalance
- Retrained the model using the balanced training data
- Compared model performance before and after SMOTE

### Why Accuracy Is Misleading
The dataset is highly imbalanced, so accuracy can be misleading. A model could predict most transactions as normal and still achieve very high accuracy while failing to detect fraudulent transactions.

Therefore, Precision, Recall, and F1-score are more useful metrics for this fraud detection task.

### Technique Used
SMOTE (Synthetic Minority Over-sampling Technique) was used to address the class imbalance.
