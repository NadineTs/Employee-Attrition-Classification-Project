# Employee-Attrition-Classification-Project

## Overview
This project analyzes employee attrition to help companies understand and reduce turnover. It uses machine learning techniques, focusing on binary classification with the AdaBoost algorithm and comparing it to K-Nearest Neighbors (KNN) and Naive Bayes (NB).

## Dataset
- **Samples**: 59,598
- **Features**: 24 (e.g., Age, Gender, Monthly Income, Job Satisfaction)
- **Target Variable**: Attrition (Stayed or Left)


## Methodology
1. **Data Preprocessing**: 
   - No missing values, categorical encoding, and scaling.
   - Split into 60% training and 40% test sets.

2. **Classification Algorithms**: 
   - KNeighborsClassifier
   - GaussianNB
   - AdaBoostClassifier

3. **Hyperparameter Tuning**: 
   - Used Grid Search to optimize hyperparameters for each model, improving prediction accuracy.

4. **Evaluation Metrics**: 
   - Accuracy, Precision, Recall, F-score, AUC.


## Results
- **AdaBoostClassifier**: Accuracy: 0.75,   AUC: 0.85       (Best performance)
- **GaussianNB**: Accuracy: 0.70,    AUC: 0.80   (Moderate performance)
- **KNeighborsClassifier**: Accuracy: 0.67,   AUC: 0.76   (Lowest accuracy)


## Conclusion
This project shows how machine learning can predict employee attrition, providing insights that help businesses improve retention strategies and maintain a stable workforce.
