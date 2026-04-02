# ewnetu_ephi_projects

Child Mortality Prediction using Machine Learning
Project Overview
This project focuses on analyzing and predicting child mortality factors using machine learning techniques. The work was conducted at the Ethiopia Public Health Institute (EPHI) under the National Data Management Center, specifically in the Data Analytics, Modeling and Visualization Division.
The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and visualization to extract meaningful insights from child mortality data.

 Dataset
•	File: champs.csv 
•	Includes variables related to: 
o	Infant causes of death 
o	Maternal factors 
o	Case types 
o	Other clinical and demographic features 

Project Workflow
1. Data Preprocessing
•	Loaded dataset using Python 
•	Checked dataset shape (rows & columns) 
•	Renamed columns for clarity 
•	Handled missing values 
•	Cleaned and prepared data for analysis 

2. Exploratory Data Analysis (EDA)
•	Analyzed: 
o	Infant underlying causes of death 
o	Maternal contributing factors 
o	Distribution of child death by case type 
•	Generated descriptive statistics 
•	Visualized key patterns 

3. Feature Engineering
•	Created relevant features 
•	Selected important variables 
•	Prepared data for model training 

4. Machine Learning Models
The following models were trained and compared:
•	Logistic Regression 
•	Support Vector Machine (SVM) 
•	AdaBoost Classifier 
•	Random Forest Classifier 
•	Gradient Boosting Classifier 
•	XGBoost 
Also built an ensemble model for improved performance.

5. Model Evaluation
Metrics Used:
•	Accuracy 
•	Precision 
•	Recall 
•	F1-score 
•	Confusion Matrix 
•	ROC-AUC Score 
ROC Curve Analysis:
•	Plotted ROC curves for all models 
•	Compared models using AUC scores 

Visualizations
🔹 ROC Curve & AUC Comparison
•	Evaluated performance of all models visually 
🔹 Feature Importance
•	Ranked features for each model 
•	Displayed using horizontal bar charts 
🔹 Key Insights
Top Infant Causes of Death
•	Visualized top 5 causes 
Top Maternal Factors
•	Identified key contributing maternal factors 
Case Type Distribution
•	Analyzed child deaths by case categories 

Technologies Used
•	Python 
•	Pandas 
•	NumPy 
•	Matplotlib / Seaborn 
•	Scikit-learn 
•	XGBoost 

Key Contributions
•	End-to-end machine learning pipeline 
•	Comparative model analysis 
•	Feature importance interpretation 
•	Data-driven insights into child mortality 

 Results
•	Identified best-performing model using cross-validation 
•	Improved predictive performance using ensemble methods 
•	Highlighted critical factors influencing child mortality

