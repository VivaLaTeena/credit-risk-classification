# Credit Risk Analysis Report

## Overview
The purpose of this analysis is to assess the performance of a machine learning model in predicting credit risk. We use logistic regression and resampled data to analyze the creditworthiness of borrowers in the context of a peer-to-peer lending services company.

## Results
- **Accuracy Score**: The logistic regression model achieved an accuracy score of 95%, indicating its overall effectiveness in distinguishing between healthy and high-risk loans.

- **Precision Score**: 
  - For healthy loans (label 0), the model demonstrated perfect precision, indicating that when it predicted a loan as healthy, it was almost always correct.
  - For high-risk loans (label 1), the model achieved an 87% precision, showing good performance in identifying loans at high risk of default.

- **Recall Score**: 
  - For healthy loans (label 0), the model achieved high recall, indicating that it correctly identified a significant portion of healthy loans.
  - For high-risk loans (label 1), the model also had high recall, showing its ability to identify a substantial portion of high-risk loans.

## Summary
The logistic regression model has proven to be highly effective in predicting both healthy and high-risk loans. It demonstrates strong precision and recall values for both classes, as well as a high overall accuracy. The oversampling of data has significantly improved the model's performance by balancing the class distribution, which is critical in credit risk assessment.

The model is recommended for use by the company to assess the creditworthiness of borrowers. Its high accuracy and balanced precision and recall values make it a reliable tool for identifying both healthy and high-risk loans. By using this model, the company can make more informed lending decisions and mitigate the risks associated with loan defaults.

The logistic regression model, fitted with oversampled data, has addressed the class imbalance problem and provides a robust solution for credit risk analysis. Its predictive capabilities are well-suited to the company's needs, ensuring sound lending practices and improved financial performance.
