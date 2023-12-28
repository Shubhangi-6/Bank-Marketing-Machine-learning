
# Bank Marketing Using Machine Learning.
- Data Source: Kaggle (CSV format)
- Data Processing
  - Converted data into a Pandas DataFrame
- Problem Statement: Predict whether a client will subscribe (yes/no) to a bank term deposit
- Exploratory Data Analysis (EDA):
  - Examined data types of columns
  - Checked the shape of the DataFrame
  - Identified and handled null values
  - Utilized `describe()` to understand data statistics
- Feature Engineering:
  - Converted data types (e.g., object to integer) using label encoding
- Feature Selection:
  - Explored linearity and correlations between columns
  - Applied a heatmap to visualize correlations
  - Utilized VIF to select features
  - Split data into training and testing sets
- Model Training:
  - Implemented Logistic Regression and assessed training and testing accuracy
  - Utilized confusion matrices and classification reports
  - Trained a Decision Tree classifier with hyperparameter tuning
  - Employed Random Forest with hyperparameter tuning
  - Introduced Adaboost to combat overfitting observed in Random Forest
- Hyperparameters:
  - For Decision Tree and Random Forest: criteria, max depth, min sample split, min sample leaf, max features
  - For Adaboost: estimators, learning rate
- Model Performance:
  - Logistic Regression: Training = ?, Testing = ?
  - Decision Tree: Training = ?, Testing = 84
  - Random Forest: Training = 1.0, Testing = 88
  - Adaboost: Training = 88, Testing = 87


