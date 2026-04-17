Titanic Survival Prediction Report
Data Science Project | Bootcamp Submission
1.	Project Description
 
This project analyzes the Titanic dataset to build a machine learning model predicting passenger survival. It follows the complete data science pipeline: preprocessing, visualization, feature engineering, and model evaluation [cite: 87, 88].
2.	Objective
 
To master data analysis and machine learning techniques by applying them to the historical Titanic passenger dataset [cite: 90].
3.	Data Preprocessing & Cleaning
 
•	Missing Values: Imputed missing 'Age' and 'Fare' values using medians [cite: 99].
•	Feature Selection: Focused on Pclass, Sex, Age, Fare, and FamilySize [cite: 104-109].
•	Encoding: Converted categorical 'Sex' into numerical values (0=Male, 1=Female).
4.	Data Visualization
 
Visual analysis revealed significant trends. Specifically, females and higher-class passengers showed much higher survival rates [cite: 100].
Figure 1: Survival Rate by Sex (Numerical )
Figure 2: Feature Correlation Heatmap  
5.	Machine Learning Model
 
A Logistic Regression model was used to classify passengers [cite: 111]. The dataset was split into 80% training and 20% testing sets.
Final Project Accuracy: 80.45%
Figure 3: Python implementation and Output in Google Colab 
6.	Model Evaluation
 
The Confusion Matrix provides a detailed look at the true positives and true negatives, confirming the model's reliability [cite: 103, 113].
Figure 4: Confusion Matrix 
7.	Conclusion
 
The project successfully demonstrates the data science workflow. With an accuracy of over 80%, the model effectively identifies key factors contributing to survival on the Titanic [cite: 124, 125].
