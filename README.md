# Credit Risk Analysis Report


## 1. Overview of the Analysis
The purpose of this analysis is to assess credit risk using machine learning models. By analyzing financial data, the goal is to predict whether a loan should be classified as "high risk" (label 1) or "low risk" (label 0). Financial institutions use such models to mitigate the risk of loan defaults, improving decision-making processes. This analysis focuses on evaluating the performance of the machine learning model in terms of its precision, recall, f1-score, and overall accuracy.

## 2. Results

- **Accuracy Score**: 99%
- **Precision Score**:
  - Class 0 (Low Risk): 100%
  - Class 1 (High Risk): 86%
- **Recall Score**:
  - Class 0 (Low Risk): 99%
  - Class 1 (High Risk): 94%
- **F1-Score**:
  - Class 0 (Low Risk): 100%
  - Class 1 (High Risk): 90%

These metrics demonstrate the model's overall high accuracy and its ability to correctly classify both high and low-risk loans. Class 0 (low-risk loans) achieves perfect precision and recall, while Class 1 (high-risk loans) shows slightly lower but still strong performance.

## 3. Summary

The results indicate that the model performs exceptionally well with an overall accuracy of 99%. The high precision and recall for low-risk loans (Class 0) suggest that the model is highly reliable in predicting low-risk loans with minimal false positives. For high-risk loans (Class 1), the recall is 94%, meaning that most high-risk loans are correctly identified, though the precision is 86%, indicating that some loans predicted as high-risk might actually be low-risk.