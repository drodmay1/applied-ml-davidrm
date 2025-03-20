# Titanic Classification Project – Lab 3

This project uses machine learning models to predict survival on the Titanic.

## Dataset
We used the Titanic dataset (from seaborn) to classify whether passengers survived based on different features.

## Models Used
- Decision Tree
- Support Vector Classifier (SVC)
- Neural Network (MLPClassifier)

## eatures Used
- alone
- age
- family_size (engineered feature)

## Evaluation Metrics
Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score

## Summary Table

| Model Type              | Case | Features Used       | Accuracy | Precision | Recall | F1-Score |
|------------------------|------|---------------------|----------|-----------|--------|----------|
| Decision Tree           | 1    | alone               | 63.00%   | 0.54      | 0.54   | 0.54     |
|                        | 2    | age                 | 63.00%   | 0.67      | 0.52   | 0.45     |
|                        | 3    | age + family_size   | 65.00%   | 0.65      | 0.65   | 0.65     |
| SVM (RBF Kernel)        | 1    | alone               | 63.00%   | 0.66      | 0.63   | 0.52     |
| SVM (Linear Kernel)     | 1    | alone               | 61.00%   | 0.38      | 0.61   | 0.47     |
| SVM (Poly Kernel)       | 1    | alone               | 61.00%   | 0.38      | 0.61   | 0.47     |
| SVM (Sigmoid Kernel)    | 1    | alone               | 55.00%   | 0.55      | 0.55   | 0.55     |
| Neural Network (MLP)    | 1    | alone               | 65.00%   | 0.64      | 0.65   | 0.65     |

## Final Thoughts
Decision Tree and Neural Network gave the best results. SVM with RBF kernel worked okay. Linear and polynomial kernels did not perform well in this case.
