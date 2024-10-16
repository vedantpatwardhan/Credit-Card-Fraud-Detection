# Credit-Card-Fraud-Detection

This project focuses on building a machine learning model to predict fraudulent transactions for a financial institution. The dataset used consists of over 6.3 million rows and 10 features related to transactions. The primary goal of this project is to detect fraudulent transactions and provide insights that can guide actionable business strategies to mitigate fraud risks.

## Project Overview
In this project, we address the following key aspects:

#### Data Preprocessing: Cleaning the dataset by handling missing values, outliers, and multicollinearity.


#### Feature Selection and Engineering: Identifying important variables that contribute to fraud detection.


#### Model Building: Developing a machine learning model using Random Forest with class balancing to handle imbalanced data.


#### Model Evaluation: Evaluating the model’s performance using the ROC-AUC score, Confusion Matrix, and other metrics.


#### Business Insights and Recommendations: Deriving key insights from the model to help prevent fraudulent activities.


## Dataset

The dataset contains 6362620 rows and 10 features, including:


step: Unit of time for the transaction (in hours).

type: Type of transaction (e.g., TRANSFER, PAYMENT).

amount: Amount of the transaction.

nameOrig: Customer initiating the transaction.

oldbalanceOrg: Initial balance before the transaction.

newbalanceOrig: Balance after the transaction.

nameDest: Recipient of the transaction.

oldbalanceDest: Initial balance of the recipient.

newbalanceDest: Balance of the recipient after the transaction.

isFraud: Indicates whether the transaction is fraudulent (1) or not (0).

## Results

ROC-AUC Score: 0.99

### Confusion Matrix: High accuracy in detecting fraud with minimal false positives.

### Feature Importance: Transaction type, amount, and balance differences are key indicators of fraud.


## Future Work

Experiment with other models like Gradient Boosting and XGBoost to compare performance.

Develop a real-time fraud detection system using this model as the foundation.


## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

