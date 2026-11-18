# Datheon_Machine_Learning:_Data_Science_Internship.

Four completed Machine Learning tasks, each in its own Jupyter notebook.

## Results

**Tasks:**
1. Multi-Class Benchmark Classification Pipeline (Iris / Wine): Logistic Regression, Decision Tree (96.7% accuracy)
2. Real Estate Housing Price Prediction (Ridge & Lasso Regression): OLS, Ridge, Lasso (R² 0.641)
3. Predictive Customer Churn Classifier (Random Forest & XGBoost): Random Forest, XGBoost (ROC-AUC 0.832)
4. NLP Sentiment Classification on Customer Reviews (TF-IDF): Naive Bayes, Logistic Regression , Working pipeline

   Note: Only 9 reviews in the provided dataset, so accuracy is not meaningful.

## Task Summaries

**Task 1:** Scales features, splits 80/20, and compares two classifiers with confusion matrices and decision boundary plots.

**Task 2:** Imputes missing values, engineers features, and tunes Ridge and Lasso with GridSearchCV. All three models score about the same.

**Task 3:** Balances the churn class with SMOTE and compares two ensemble models using ROC curves and feature importances.

**Task 4:** Cleans text, builds TF-IDF features, and includes a predict_sentiment() function for custom input.

## Project Structure

1. **Task_1 (Multi-Class Benchmark Classification Pipeline (Iris / Wine))**:
    - Task_1.ipynb
    - iris.csv
2. **Task_2 (Real Estate Housing Price Prediction (Ridge & Lasso Regression))**:
    - Task_2.ipynb
    - housing.csv
3. **Task_3 (Predictive Customer Churn Classifier (Random Forest & XGBoost))**:
    - Task_3.ipynb
    - Telco-Customer-Churn.csv
4. **Task_4 (NLP Sentiment Classification on Customer Reviews (TF-IDF))**:
    - Task_4.ipynb
    - sentiment_reviews.csv

## How to Run
Open each notebook from inside its own folder.
