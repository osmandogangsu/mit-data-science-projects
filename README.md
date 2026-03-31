MIT Data Science and Machine Learning: Making Data-Driven Decisions
Osman Dogan | Doctoral Candidate, Department of Communication, Georgia State University
Program: MIT Schwarzman College of Computing / MIT Institute for Data, Systems, and Society (IDSS)
Duration: 12 weeks (intensive remote program)
Completed: April 2023
Certificate Verification: verify.mygreatlearning.com/HWOQRXFH

About
This repository contains six hands-on projects completed during the MIT IDSS professional certificate program in Data Science and Machine Learning. The program covered the full machine learning pipeline — from exploratory data analysis and statistical inference through supervised and unsupervised learning, deep learning, and recommendation systems. All projects address real-world business problems using industry-standard Python libraries.

Note on datasets: Datasets were provided by MIT IDSS for educational purposes and are not included in this repository. Each project section below describes the dataset used. Notebooks retain all output cells (visualizations, model metrics, classification reports) so that the full analysis is visible without re-execution.


Projects
01 · Foundations — Python and Statistics
Pima Diabetes Analysis · View Project
Exploratory data analysis of clinical predictors of diabetes onset among female patients of Pima Indian heritage. Conducted distribution analysis, outlier detection, correlation mapping, and data quality assessment to derive actionable insights from health data.
Techniques: Descriptive Statistics, Histograms, Boxplots, Correlation Heatmaps, Data Cleaning
Dataset: Pima Indian Diabetes dataset — 768 records × 9 features (pregnancies, glucose, blood pressure, skin thickness, insulin, BMI, diabetes pedigree function, age, outcome)

02 · Classification and Hypothesis Testing
Tourism Package Purchase Prediction · View Notebook
Built and compared classification models to predict customer likelihood of purchasing a travel package for a tourism company. Conducted hypothesis testing to validate feature significance and evaluated model performance through confusion matrices, ROC-AUC scores, and hyperparameter tuning.
Techniques: Logistic Regression, Decision Trees, Random Forest, SVM, Hypothesis Testing, GridSearchCV, ROC-AUC
Dataset: Tourism company customer data — demographic attributes, trip history, interaction records, and purchase outcomes

03 · Ensemble Methods — Churn Prediction
Credit Card Users Churn Prediction · View Notebook
Developed predictive models to identify credit card customers at risk of churning for a banking institution. Compared multiple classifiers with feature scaling and cross-validation, optimizing for both precision and recall to balance the business cost of false positives and false negatives.
Techniques: Logistic Regression, Decision Trees, Random Forest, SVM, Cross-Validation, ROC-AUC, GridSearchCV, StandardScaler
Dataset: BankChurners.csv — credit card holder profiles including demographics, credit limit, transaction history, utilization ratio, and attrition flag

04 · Ensemble Methods — Employee Attrition
Employee Attrition Prediction · View Notebook
Built an end-to-end classification pipeline to predict employee attrition for a multinational health consultancy. Applied bagging classifiers alongside standard algorithms, with feature scaling, hyperparameter tuning, and comprehensive model comparison to identify the most reliable predictor.
Techniques: Logistic Regression, Decision Trees, Random Forest, SVM, Bagging Classifier, GridSearchCV, StandardScaler
Dataset: HR_Employee_Attrition_Dataset.xlsx — 1,470 employee records × 35 features including demographics, job role, compensation, satisfaction scores, and attrition status

05 · Recommendation Systems
Amazon Product Reviews — Recommendation Engine · View Notebook
Built collaborative filtering recommendation systems for Amazon electronic product reviews. Implemented both memory-based (KNN) and model-based (SVD) approaches, evaluating recommendation quality through hyperparameter optimization.
Techniques: KNN-Based Collaborative Filtering, Singular Value Decomposition (SVD), Surprise Library, GridSearchCV
Dataset: Amazon electronics product ratings — user IDs, product IDs, ratings, and timestamps
Movie Recommendation System · View Project
Developed three recommendation approaches for a movie streaming platform: rank-based recommendations for cold-start users, similarity-based collaborative filtering using Pearson correlation, and matrix factorization-based collaborative filtering using SVD. Compared memory-based and model-based methods to optimize personalized suggestions.
Techniques: Rank-Based Filtering, Pearson Correlation, Matrix Factorization, SVD, KNN, Surprise Library, SciPy
Dataset: Movie ratings dataset — user IDs, movie IDs, ratings, and timestamps

Tools and Libraries
CategoryToolsLanguagesPythonData ManipulationPandas, NumPyVisualizationMatplotlib, SeabornMachine LearningScikit-learn (classification, regression, model selection, preprocessing)RecommendationSurprise, SciPyEnvironmentJupyter Notebook, Google Colab

Repository Structure
mit-data-science-projects/
├── README.md
├── 01-foundations-python-statistics/
│   └── Pima_Diabetes_Analysis_Osman_Dogan.html
├── 02-classification-hypothesis-testing/
│   └── Tourism_Package_Prediction.ipynb
├── 03-ensemble-methods-churn-prediction/
│   └── Credit_Card_Users_Churn_Prediction.ipynb
├── 04-employee-attrition-prediction/
│   └── Case_Study_Employee_Attrition.ipynb
└── 05-recommendation-systems/
    ├── Product_Recommendation_Solution.ipynb
    └── Movie_Recommendation_System.html

About the Author
Osman Dogan is a doctoral candidate in the Department of Communication at Georgia State University, researching media framing and digital communication through quantitative content analysis. He holds a professional certificate in Data Science and Machine Learning from MIT IDSS and brings professional experience as a former Digital News Editor at TRT World. He is quadrilingual in Turkish, English, French, and Arabic.

LinkedIn: www.linkedin.com/in/osman-doğan-83b50a333
Email: osmandogangsu@gmail.com


These projects were completed as part of the MIT IDSS Data Science and Machine Learning: Making Data-Driven Decisions professional certificate program (April 2023). 
