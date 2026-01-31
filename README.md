# Predicting-fraudulent-transactions-using-Machine-Learning
This project focuses on proactive detection of fraudulent financial transactions using machine learning techniques.   The goal is to build an end-to-end fraud detection pipeline that not only predicts fraudulent activities but also provides business insights and prevention strategies.
Data Cleaning
- Checked for missing values  
- Removed non-informative identifier columns  
- Encoded categorical variables  
- Analyzed outliers (not aggressively removed, as frauds are extreme by nature)  
-Checked multicollinearity using correlation analysis

Exploratory Data Analysis
- Distribution of transaction amounts  
- Correlation heatmaps  
- Class imbalance analysis  

Feature Selection
Features were selected based on:
- Business understanding from the data dictionary  
- Correlation analysis  
- Feature importance from tree-based models  

Model Building
Two models were implemented:
- *Logistic Regression* – baseline and interpretable model  
- *Random Forest Classifier* – handles non-linearity and class imbalance effectively  

Model Evaluation
Due to class imbalance, the following metrics were prioritized:
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

Feature Importance Analysis
Random Forest feature importance was used to identify the most influential factors contributing to fraud.

 Key Fraud Indicators
- High transaction amounts  
- Sudden changes in account balance  
- Certain transaction types prone to fraud  
- Abnormal transaction behavior patterns  

Fraud Prevention Strategies
Based on model insights, the following preventive measures are recommended:
- Real-time transaction monitoring  
- Multi-factor authentication  
- Transaction limits and velocity checks  
- Alerts for abnormal user behavior  
- Periodic retraining of fraud detection models  

Measuring Effectiveness
The effectiveness of implemented prevention strategies can be measured using:
- Reduction in fraud rate over time  
- Improvement in recall and F1-score  
- Decrease in false negatives  
- Continuous model performance monitoring  
- A/B testing of fraud prevention rules  



## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook
