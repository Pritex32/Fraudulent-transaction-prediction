# Fraud Detection and Classification Model Development
## Project Overview:

Developed a machine learning model to predict whether a transaction is fraudulent based on available transaction data.
Implemented a classification model with the target variable indicating fraud status (1) or non-fraud (0).
Key Contributions:

## Data Preprocessing: Cleaned and transformed a large dataset (Fraud.csv), handling missing values by removing records with null entries and addressing duplicate data. Performed data normalization and outlier detection using the interquartile range (IQR) method and capped outliers to maintain model integrity.

## Feature Engineering:

Renamed columns for better understanding and handled categorical variables by applying Label Encoding for easy integration into the machine learning models.
Checked for multicollinearity using the Variance Inflation Factor (VIF) and dropped highly correlated features.
Class Imbalance Handling:

Identified class imbalance and applied SMOTE (Synthetic Minority Oversampling Technique) to resample the data and balance the classes.
Model Development and Evaluation:

Applied and compared multiple machine learning algorithms including Decision Tree, K-Nearest Neighbors (KNN), Random Forest, and Logistic Regression.
Evaluated models using accuracy scores, confusion matrix, and classification reports, selecting Random Forest as the optimal model due to its superior performance.
Tools and Technologies:

Python (Pandas, NumPy, Matplotlib, Seaborn)
Scikit-learn (DecisionTreeClassifier, KNeighborsClassifier, RandomForestClassifier, LogisticRegression)
SMOTE for handling class imbalance
Data visualization techniques (heatmaps, box plots) for feature selection and data analysis
Achievements:

Successfully handled outliers and transformed data to improve model performance.
Achieved a high model accuracy, leading to the selection of Random Forest as the best classifier for the fraud detection problem.
