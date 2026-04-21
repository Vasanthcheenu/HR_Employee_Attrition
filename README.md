📊 HR Analytics — Employee Attrition Prediction


A machine learning project to predict employee attrition and uncover key factors driving workforce turnover using real-world HR data.


🚀 Project Overview


This project focuses on predicting whether an employee will leave the organization (Attrition: Yes/No) using supervised machine learning models. It also provides actionable insights for HR teams to improve retention strategies.


📁 Dataset: IBM HR Analytics (1,470 employees, 35 features)

🎯 Objective: Predict attrition & identify key drivers

🧠 Approach: EDA + ML Models + Ensemble Learning

📌 Key Highlights

📉 Attrition Rate: 16.1%

👥 Total Employees: 1,470

📊 Clean dataset (No missing values)

⚖️ Imbalanced data handled via stratified split

🔍 Exploratory Data Analysis (EDA)


Key insights discovered:


🔥 Overtime is the strongest predictor

30.5% attrition (OT) vs 10.4% (No OT)

💰 Salary impacts retention

Employees who left earn ~$2,000 less/month


😊 Low job satisfaction = high attrition

Level 1: 22.8% vs Level 4: 11.3%

👨‍💼 High-risk roles

Sales Representatives (39.8%)

Lab Technicians (23.9%)

HR (23.1%)

🎯 Age group 25–35 most likely to leave

⚙️ Tech Stack

Language: Python

Platform: Juptior Notebook

Libraries:

pandas, numpy

seaborn, matplotlib

scikit-learn

xgboost


Combines predictions from all models to improve accuracy and stability.



📊 Model Pipeline

Data Loading & Exploration

Data Cleaning (drop constants)

Encoding categorical variables

Feature scaling

Train-test split (80/20, stratified)

Model training:

Logistic Regression

Random Forest

XGBoost

Ensemble using Voting Classifier

Evaluation using Precision, Recall, F1-score


🔑 Key Attrition Drivers

Overtime

Job Satisfaction

Monthly Income

💡 Business Recommendations

⏱️ Reduce overtime workload

💰 Improve compensation for low-income roles

📊 Conduct regular satisfaction surveys

🚀 Create fast-track career growth programs

🏠 Introduce flexible/hybrid work

⚠️ Deploy ML model for proactive risk detection



🏁 Conclusion

This project demonstrates a near production-ready ML pipeline for attrition prediction.

The insights are highly actionable:

Overtime employees are 3x more likely to leave

Lower salary strongly correlates with attrition

Certain job roles are at critical risk

With further improvements, this can be deployed as a real-time HR decision support system.
Job Role
Age (25–35)
Work-Life Balance
