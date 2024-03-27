**Performance metrics (classification report)** for each model on the **balanced dataset**: 

### Logistic Regression:

|           | Precision | Recall | F1-Score | Support |
|-----------|-----------|--------|----------|---------|
| Not Fraud | 0.93      | 0.99   | 0.96     | 69      |
| Fraud     | 0.99      | 0.93   | 0.96     | 73      |
| Accuracy  |           |        | 0.96     | 142     |
| Macro Avg | 0.96      | 0.96   | 0.96     | 142     |
| Weighted Avg | 0.96   | 0.96   | 0.96     | 142     |

### Shallow NN:

|           | Precision | Recall | F1-Score | Support |
|-----------|-----------|--------|----------|---------|
| Not Fraud | 0.86      | 1.00   | 0.93     | 69      |
| Fraud     | 1.00      | 0.85   | 0.92     | 73      |
| Accuracy  |           |        | 0.92     | 142     |
| Macro Avg | 0.93      | 0.92   | 0.92     | 142     |
| Weighted Avg | 0.93   | 0.92   | 0.92     | 142     |

### Random Forest:

|           | Precision | Recall | F1-Score | Support |
|-----------|-----------|--------|----------|---------|
| Not Fraud | 0.91      | 1.00   | 0.95     | 69      |
| Fraud     | 1.00      | 0.90   | 0.95     | 73      |
| Accuracy  |           |        | 0.95     | 142     |
| Macro Avg | 0.95      | 0.95   | 0.95     | 142     |
| Weighted Avg | 0.96   | 0.95   | 0.95     | 142     |

### Gradient Boosting:

|           | Precision | Recall | F1-Score | Support |
|-----------|-----------|--------|----------|---------|
| Not Fraud | 0.93      | 0.94   | 0.94     | 69      |
| Fraud     | 0.94      | 0.93   | 0.94     | 73      |
| Accuracy  |           |        | 0.94     | 142     |
| Macro Avg | 0.94      | 0.94   | 0.94     | 142     |
| Weighted Avg | 0.94   | 0.94   | 0.94     | 142     |

### SVC:

|           | Precision | Recall | F1-Score | Support |
|-----------|-----------|--------|----------|---------|
| Not Fraud | 0.93      | 0.97   | 0.95     | 69      |
| Fraud     | 0.97      | 0.93   | 0.95     | 73      |
| Accuracy  |           |        | 0.95     | 142     |
| Macro Avg | 0.95      | 0.95   | 0.95     | 142     |
| Weighted Avg | 0.95   | 0.95   | 0.95     | 142     |
