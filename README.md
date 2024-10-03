# Credit-Card-Fraud-Detection
This project was directed by the "Building Credit Card Fraud Detection with Machine Learning" course on Udemy. Machine learning models such as logistic regression, random forest, and support vector machine (SVM) are built using Python and libraries like pandas, matplotlib, and scikit-learn.

Overview of the key steps covered in this project:

Data Exploration:

Began by loading the dataset, which contains 1 million transactions with 8 features (columns), such as distance_from_home, distance_from_last_transaction, ratio_to_median_purchase_price, repeat_retailer, used_chip, used_pin_number, and fraud (target variable).
Initial exploratory analysis included inspecting the dataset’s structure, checking for missing values, visualizing distributions, and understanding summary statistics of the features.

Data Preprocessing:
Checked for any duplicate records and missing values. In this case, no missing values or duplicates are found.
Data is then splitted into training and testing sets, ensuring a balanced ratio between fraudulent and non-fraudulent transactions.

Data Visualization:
Pie charts are created to visualize the proportion of fraudulent vs. non-fraudulent transactions in both chip and pin transactions.
Sequences of non-fraudulent transactions followed by a fraudulent one are explored to understand patterns.

Feature Engineering:
Calculated features like the correlation between the ratio to median purchase price and fraud occurrence, which showed a moderate correlation.
Fraud cases are also explored in online vs. offline transactions, and the fraud rates for each type are calculated.

Model Building:
Multiple machine learning models are built:

Random Forest: A random forest classifier is trained, and feature importance is calculated. The model predicts whether a transaction is fraudulent based on input features.

Logistic Regression: A logistic regression model is also built for fraud detection, after scaling the features.

Support Vector Machine (SVM): An SVM model is constructed with feature scaling to estimate probabilities of fraud.
Evaluation:

Model's performance is evaluated using metrics such as precision, recall, F1 score, and accuracy (chose to evaluate the metrics of the logistic regression model). The models are tested with new transaction data, and predictions are made regarding the legitimacy of the transactions.

Overall, this project demonstrated a complete workflow for fraud detection using machine learning, from data exploration and preprocessing to model training and evaluation. The use of different algorithms and the detailed analysis of fraud rates in various transaction types provide a comprehensive approach to understanding and mitigating credit card fraud.

