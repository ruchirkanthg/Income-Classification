# Income-Classification
This project focuses on building a binary classification model to predict income levels based on various features. The primary goal is to develop a robust machine learning model that accurately classifies individuals into two income categories: "&lt;=50K" or ">50K"

# Data
Title: Adult Income dataset
Source: UCI Machine Learning Repository
URL: UCI Adult dataset
Description: The dataset contains demographic information, such as age, education, occupation, and marital status, among other attributes. The target variable is binary and indicates whether an individual earns more than $50,000 annually (positive class) or not (negative class).

Attributes:
Age: Age of the individual.

Workclass: Type of employment (e.g., Private, Self-emp-not-inc, Local-gov).
Education: Highest level of education achieved.
Occupation: Type of occupation.
Marital Status: Marital status of the individual.
Relationship: Relationship status in the family.
Race: Race of the individual.
Sex: Gender of the individual.
Capital Gain: Capital gains earned by the individual.
Capital Loss: Capital losses incurred by the individual.
Hours per Week: Average number of working hours per week.
Native Country: Country of origin.
Target Variable:
Income: Binary variable indicating whether the individual earns more than $50,000 annually (positive class) or not (negative class).

# Unique concepts used 
1) SMOTE - Synthetic Minority Over-sampling Technique
   
SMOTE is a technique used in machine learning to address the class imbalance problem in binary and multiclass classification. Class imbalance occurs when one class in the dataset has significantly fewer instances than     the other class(es), leading to biased model training and potentially poor performance on the minority class. 

SMOTE works by generating synthetic examples of the minority class, thereby balancing the class distribution. It does this by creating synthetic samples that are interpolations of existing minority class instances.

2) SHAP - SHapley Additive exPlanations

SHAP values are based on cooperative game theory and Shapley values, and they aim to fairly distribute the contribution of each feature to the prediction of a specific instance. Basically SHAP helps to determine how important each feature in the dataset is to the target variable which in this case is Income. 



# Machine Learning Models
1) Logistic Regression (with and without using scikit-learn library)
2) Discrete Naive Bayes - Raw Coded
3) Decision tree - Raw Coded
4) Neural Network

# Performance Metrics 
The following performance metrics were used to identify the best performing model among the four used: 
1) Accuracy
2) Precision
3) f1 score
4) Recall

For generalising the performance, cross validation has been done so that overfitting is eliminated and the models fit the data efficiently. 



