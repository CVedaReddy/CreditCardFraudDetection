# CreditCardFraudDetection

Credit card fraud is a significant issue faced by financial institutions and customers worldwide. Fraudulent transactions can lead to substantial financial losses and undermine consumer trust in digital payment systems.
Data science, particularly machine learning, offers powerful tools to identify suspicious transactions and reduce the incidence of fraud.

DATASET:

The dataset contains transactions made by European cardholders in September 2013. It includes transactions that occurred over two days, with 492 frauds out of 284,807 transactions, making the dataset highly unbalanced. The positive class (frauds) accounts for only 0.172% of all transactions.

The dataset is as follows : https://drive.google.com/file/d/1u_9Zr5cEZYSCn-YhG4Ymrct6oHcNKTNC/view?usp=sharing

Features used:
1. Data preprocessing:
  Normalize and standardize the 'Time' and 'Amount' features.
2. Exploratory Data Analysis (EDA):
  Analyze transaction patterns. Visualize the distribution of fraud vs valid transactions. Identify correlations between features.
3. Feature Engineering:
  Utilize the 'Time' and 'Amount' features for additional insights.
4. Model development:
   Evaluate various machine learning algorithms (e.g., Logistic Regression, Random Forest, Gradient Boosting, Neural Networks). Address class imbalance 
   using techniques such as SMOTE (Synthetic Minority Over-sampling Technique) or class weighting. Perform hyperparameter tuning to optimize model 
   performance.
5. Model evaluation
   Use cross-validation to assess model robustness. Evaluate performance using metrics such as Precision, Recall, F1-Score, and particularly the Area Under 
   the Precision-Recall Curve (AUPRC).

Success metrics:

   AUPRC: The primary metric to measure the model's performance in handling imbalanced data.
   
   Precision and Recall: Measure the model's effectiveness in detecting fraud without generating excessive false alarms.
   
   F1-Score: Balance between precision and recall.
   
   ROC-AUC: Model’s ability to distinguish between classes.
