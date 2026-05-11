# **Customer Churn Prediction using Machine Learning**

1. **Project Overview**

This project focuses on predicting customer churn in the banking sector using Machine Learning techniques. Customer churn prediction helps banks identify customers who are likely to leave, enabling proactive retention strategies.
The dataset contains 10,000 customer records with demographic and banking-related features such as age, balance, country, credit history, and account activity.

2. **Business Problem**

The bank is facing a customer churn rate of approximately 20.37%, meaning a significant portion of customers are leaving the bank.

 **Key Business Challenges**
 - Loss of valuable and long-term customers
 - Higher churn among senior customers
 - Germany-based customers showing higher churn tendency
 - Inactive customers are more likely to leave
 - Imbalanced dataset affecting model performance
   
3. **Project Objectives**

 - Predict customers likely to churn
 - Analyze customer behavior patterns
 - Compare Machine Learning models
 - Support customer retention strategies
   **Dataset Information**
 - Total Records: 10,000
 - Target Variable: Churn (0 = No, 1 = Yes)
   **Features Used**
 - Credit Score
 - Age
 - Balance
 - Gender
 - Country
 - Number of Products
 - Credit Card Status
 - Active Member Status
4. **Workflow**
 1. **Data Preprocessing :**
 - Handled missing values
 - Removed duplicates
 - Cleaned and formatted data
2. **Exploratory Data Analysis (EDA)**
 - Churn distribution analysis
 - Country-wise churn trends
 - Age and balance distribution
 - Active member behavior analysis
 - Statistics Analysis
3. **Feature Engineering**
 - Label Encoding
 - One-Hot Encoding (Country feature)
 - Feature scaling using StandardScaler
4. **Handling Imbalanced Data**
 - Applied SMOTE (Synthetic Minority Oversampling Technique) to balance classes
5. **Model Building**
 - XGBoost Classifier
 - Gradient Boosting Classifier
6. **Model Evaluation**
 - Accuracy Score
 - Classification Report
 - Confusion Matrix
 - Precision, Recall, F1-score
5. **Model Performance**
 - XGBoost Accuracy: 83%
 - Gradient Boosting Accuracy: 84%
6.  **Best Performing Model**

 - **Gradient Boosting Classifier performed slightly better in overall accuracy. However, XGBoost showed stronger performance in identifying churn customers by achieving better recall and lower false negatives.**

7.  **Key Business Insights**
 - Senior customers show higher churn probability
 - Inactive members are more likely to leave
 - Germany has the highest churn rate
 - High-balance customers also show churn tendency
 - Active members are more loyal
 - France shows lower churn compared to Germany
8. **Recommendations**
 1. **Customer Retention Strategy**
 - Focus on high-risk groups: senior, inactive, Germany-based customers
 2. **Engagement Improvement**
 - Run targeted engagement campaigns
 - Offer personalized promotions
 - Improve digital banking experience
 3. **Targeted Marketing**
 - Loyalty rewards for long-term customers
 - Benefits for high-balance customers
 4. **Business Implementation**
 - Deploy ML model for churn prediction
 - Monitor churn probability regularly
 - Build early warning system
10. **Technologies Used**
 - Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, SMOTE, VS Code

11. **Conclusion**

**Machine Learning models were successfully developed to predict customer churn using banking data. After preprocessing, feature engineering, scaling, and balancing the dataset using SMOTE, both XGBoost and Gradient Boosting models were evaluated.
Gradient Boosting performed slightly better overall, while XGBoost showed stronger capability in identifying churn customers. This project demonstrates how Machine Learning can support businesses in reducing customer loss and improving retention strategies through data-driven decision-making.**
