# Credit_Risk_Analysis
## Overview
Loan data was tabulated for >100k people. The following analysis contains 6 different Machine Learning models that all aim to predict the loan risk of a borrower.

## Results (Models and Performance)
The 6 Machine Learning models used in this analysis are: 
  1. Naive Random Oversampling
      - Balanced Accuracy: 0.64
      - Precision: 0.99
      - Recall Scores
          - High Risk: 0.72
          - Low Risk: 0.56
  2. SMOTE Oversampling
      - Balanced Accuracy: 0.66
      - Precision: 0.99
      - Recall Scores
          - High Risk: 0.62
          - Low Risk: 0.69
  3. Cluster Centroid Undersampling
      - Balanced Accuracy: 0.66
      - Precision: 0.99
      - Recall Scores
          - High Risk: 0.62
          - Low Risk: 0.69
  4. SMOTEEN Combination Sampling
      - Balanced Accuracy: 0.67
      - Precision: 0.99
      - Recall Scores
          - High Risk: 0.73
          - Low Risk: 0.60
  5. Balanced Random Forest
      - Balanced Accuracy: 0.79
      - Precision: 0.99
      - Recall Scores
          - High Risk: 0.70
          - Low Risk: 0.87
  6. **Easy Ensemble Classifier**
      - **Balanced Accuracy: 0.93**
      - **Precision: 0.99**
      - **Recall Scores**
          - **High Risk: 0.92**
          - **Low Risk: 0.94**

## Summary
The results section above clearly identifies the Easy Ensemble Classifier as the top model due to its >90% balanced accuracy which is unmatched by any other model. If no further model assessments will be performed, the Easy Ensemble Classifier mode should be utilized for loan risk analyses.
