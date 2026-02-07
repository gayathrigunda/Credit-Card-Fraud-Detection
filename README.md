📌 Project Overview
Credit card fraud is a major issue in financial systems. This project focuses on detecting fraudulent transactions 
using machine learning classification algorithms. The model is trained on real transaction data and evaluated using 
multiple performance metrics to identify the most effective algorithm. 

🎯 Objective 
To build and compare machine learning models that can accurately classify credit card transactions as fraudulent or 
non-fraudulent using:
1. Naïve Bayes
2. Decision Tree
3. Logistic Regression

📂 Dataset
Source: Kaggle – Credit Card Fraud Detection Dataset
https://www.kaggle.com/datasets/jellalkami/creditcard-dataset
- Total transactions: 284,807
- Fraudulent transactions: 492
- Highly imbalanced dataset

⚙️ Methodology
1. Data Preprocessing
- Handled missing values
- Standardized numerical features
- Prepared data for model training
  
2. Exploratory Data Analysis (EDA)
- Visualized data distribution
- Analyzed class imbalance
- Checked feature correlations
  
3. Handling Imbalanced Data
- Applied SMOTE (Synthetic Minority Oversampling Technique) to balance fraud and non-fraud samples

4. Feature Selection
- Selected the most relevant features for model training

5. Model Training
The following models were implemented:
i. Naïve Bayes
ii. Decision Tree
iii. Logistic Regression
Each model was trained on the training dataset and tested on unseen data.

📊 Model Evaluation
Models were evaluated using:
a. Accuracy
b. Precision
c. Recall
d. F1-Score
e. ROC-AUC Score
f. Confusion Matrix

🏆 Results
1. Naïve Bayes: Fast but lower precision due to simplified assumptions
2. Decision Tree: Good accuracy but showed signs of overfitting
3. Logistic Regression: Best overall performance with balanced precision and recall

✅ Logistic Regression was identified as the most effective model for this dataset.

🧠 Conclusion
This project demonstrates how machine learning can be used to detect fraudulent credit card transactions. Logistic Regression provided the most reliable results. Future improvements could include:
1. Ensemble methods (Random Forest, Gradient Boosting)
2. Real-time fraud detection system
3. Deep learning models

🛠️ Technologies Used
1. Python
2. Pandas
3. NumPy
4. Scikit-learn
5. Matplotlib
6. Seaborn
7. Imbalanced-learn (SMOTE)
8. Jupyter Notebook

