# Company-Bankruptcy-Prediction
Analysis of financial rations across many companies to determine whether they declare bankruptcy or not.

________________________________

We used random forest as a classifier model. Before that, we performed multiple feature elimination and feature extraction methods:
1. Pearson coefficient for correlation amongst features
2. Recursive Feature Elimination using Cross Validation
3. Embedded method (Binomial Logistic Regression with Lasso Regularization)
4. Permutation Feature Importance
5. Principal Component Analysis
6. Standard Scaler
7. MinMax Scaler
8. Max Absolute Scaler
9. Robust Scaler
10. Power Transformer
11. Quantile Transformer
12. Normalizer
13. SMOTE
14. Stratified Sampling
