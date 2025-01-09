# Titanic Survival Prediction Project

## Aim
The primary goal of this project is to predict the survival of passengers aboard the Titanic using machine learning models. A detailed comparative analysis of various models was conducted to determine the most accurate predictor. 

## Dataset
The dataset includes information about passengers such as age, gender, ticket class, family size, and survival status. Features were preprocessed and transformed for compatibility with machine learning algorithms.

## Steps Undertaken
1. **Data Preprocessing**:
    - Handled missing values for age and embarked columns.
    - Encoded categorical variables like gender and embarked.
    - Standardized numerical features.

2. **Model Implementation**:
    - Logistic Regression
    - Support Vector Machines (SVM)
    - Random Forest Classifier
    - Decision Tree

3. **Model Evaluation**:
    - Performance metrics: Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
    - Cross-validation for robust evaluation.

## Comparative Analysis of Models

### Results
| Model                  | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|------------------------|----------|-----------|--------|----------|---------|
| Logistic Regression    | 80.97%   | 77.5%     | 71.8%  | 74.6%    | 82.0%   |
| SVM                    | 65.67%   | 80.1%     | 75.3%  | 77.6%    | 85.1%   |
| Random Forest          | 81.72%   | 83.7%     | 80.0%  | 81.8%    | 88.2%   |
| Decision Tree          | 74.63%   | 84.9%     | 81.4%  | 83.1%    | 89.3%   |


## Visualizations
- Confusion matrices for all models.
- ROC curves for a comparative view of model performance.
- Feature importance chart from tree-based models like Random Forest.

![image](https://github.com/user-attachments/assets/88eb7ab1-dc77-4c50-883f-e8eb2421ffbe)

![image](https://github.com/user-attachments/assets/b0112ac1-6698-4856-8ba7-2ce11945d662)

![image](https://github.com/user-attachments/assets/3ac752ac-3930-428b-b67f-b3e32939e998)

![image](https://github.com/user-attachments/assets/4c79b42c-922b-41a0-814d-c52fa5df60b9)

![image](https://github.com/user-attachments/assets/a42f3dde-9026-4aa4-bda6-31714404a88b)

![image](https://github.com/user-attachments/assets/e83807c4-b218-4012-966c-bff45d2a0b64)

![image](https://github.com/user-attachments/assets/7fe0a15a-3f11-4756-b4c7-f966074b3a74)



