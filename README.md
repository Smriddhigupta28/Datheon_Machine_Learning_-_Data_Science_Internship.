# Datheon_Machine_Learning:_Data_Science_Internship.

Four completed ML tasks, each in its own Jupyter notebook.

## Results

Tasks:
1. Iris Classification: Logistic Regression, Decision Tree (96.7% accuracy)
2. Housing Price Prediction: OLS, Ridge, Lasso (R² 0.641)
3. Customer Churn Prediction: Random Forest, XGBoost (ROC-AUC 0.832)
4. Sentiment Classification: Naive Bayes, Logistic Regression , Working pipeline
   Note: Only 9 reviews in the provided dataset, so accuracy is not meaningful.

## Task Summaries

**Task 1:** Scales features, splits 80/20, and compares two classifiers with confusion matrices and decision boundary plots.

**Task 2:** Imputes missing values, engineers features, and tunes Ridge and Lasso with GridSearchCV. All three models score about the same.

**Task 3:** Balances the churn class with SMOTE and compares two ensemble models using ROC curves and feature importances.

**Task 4:** Cleans text, builds TF-IDF features, and includes a predict_sentiment() function for custom input.

## Project Structure

1. Task_1_Iris_Classification:
    - Task_1.ipynb
    - iris.csv
2. Task_2_Housing_Regression:
    - Task_2.ipynb
    - housing.csv
3. Task_3_Churn_Prediction:
    - Task_3.ipynb
    - Telco-Customer-Churn.csv
4. Task_4_Sentiment_NLP:
    - Task_4.ipynb
    - sentiment_reviews.csv

## How to Run
Open each notebook from inside its own folder.
