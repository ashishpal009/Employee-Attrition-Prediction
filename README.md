Project Overview
This project aims to predict whether an employee will leave the company based on various factors such as satisfaction level, last evaluation, number of projects, salary, and more. The dataset used for this project contains various features that are analyzed and processed to build a predictive model.

Libraries Used
pandas: For data manipulation and analysis.
numpy: For numerical computations.
matplotlib: For data visualization.
seaborn: For statistical data visualization.
scikit-learn: For machine learning algorithms and preprocessing.
Dataset
The dataset used in this project is Dataset01-Employee_Attrition.csv. The target variable is 'Left', where 0 indicates the employee stayed with the company, and 1 indicates the employee left the company.

Key Steps in the Project
Data Loading: The dataset is loaded using pandas.read_csv() and basic exploration is performed.
Data Cleaning: The dataset is checked for duplicates and missing values, and cleaned accordingly.
Exploratory Data Analysis (EDA):
Distribution of the target variable (left) is analyzed.
Impact of salary on employee retention is explored using crosstab and bar charts.
Department-wise employee retention rate is also visualized.
Numerical features are explored using box plots.
Feature Engineering:
Categorical variables such as salary and Department are encoded using LabelEncoder.
The dataset is then split into features (X) and the target variable (Y).
Data Splitting: The dataset is split into training and testing sets using train_test_split.
Scaling: Features are scaled using StandardScaler to standardize the data before model training.
Model Deployment:
Random Forest Classifier is used as the primary model.
Model is trained, and predictions are made on the test set.
Model Evaluation:
Performance of the model is evaluated using confusion matrix, accuracy score, and classification report.
Feature importance is analyzed and visualized.
Cross-Validation: 5-fold cross-validation is used to validate the model's performance.
Hyperparameter Tuning: GridSearchCV is used to find the best parameters for the Random Forest model.
Results
The Random Forest model showed [mention the accuracy score here] accuracy after tuning. The model's performance was also validated using cross-validation, resulting in an average score of [mention cross-validation score here].

Future Work
Exploring more sophisticated models.
Dealing with data imbalance using techniques such as SMOTE.
Including more features or external data sources for improved predictions.
How to Run the Project
Clone the repository.
Install the required libraries listed in requirements.txt.
Run the Jupyter Notebook file to reproduce the results.
