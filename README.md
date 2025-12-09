# Titanic Survival Prediction

I took up this competition as a beginner data scientist to test my skills, strengthen my foundations, and get comfortable with a real-world machine learning workflow. The Titanic dataset is a classic starting point, and this project helped me understand everything from data cleaning to model building and evaluation.

# What I Did

* Basic EDA, to understand the dataset better and what factors influenced survival.
* Cleaned the dataset and handled missing values.
* Extracted Titles from Names.
* Encoded categorical variables.

# Models I Trained

* Logistic Regression – baseline model
* Random Forest Classifier
* KNN
* XGBoost

Hyperparameter tuning is planned using GridSearchCV and RandomizedSearchCV.

# Baseline Results 

Mean of Cross Validated Scores
* RandomForestClassifier = 80.14%
* LogisticRegression = 82.60% **(Highest)**
* KNN = 72.39% (Rejected)
* XGB = 82.40%

# After Hyperparameter Tuning

* LogisticRegression = 82.60%
* RandomForest = 85.18% (Best)
* XGBoost = 84.06%.

# Results on Test Data (Kaggle Submissions)

* RandomForestClassifier = 0.76555
* LogisticRegression = 0.77033 **(Highest)**
* XGB = 0.76794

# Dataset

Used the Kaggle Titanic dataset: (https://www.kaggle.com/competitions/titanic/data)
