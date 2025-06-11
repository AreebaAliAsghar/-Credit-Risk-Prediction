# Credit Risk Prediction

## Objective
Predict whether a loan applicant is likely to default or not, using historical loan data. This is a typical binary classification problem that is crucial for financial institutions to automate credit risk assessments.

## Dataset
- Source: [Kaggle - Loan Prediction Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)
- The dataset contains demographic and financial information about loan applicants, including:
  - Gender, Married status, Dependents, Education
  - Self Employed, Applicant Income, Coapplicant Income
  - Loan Amount, Loan Amount Term, Credit History
  - Property Area, Loan Status (target)

## Approach
1. **Data Cleaning & Handling Missing Values**  
   - Numerical missing values filled with median.  
   - Categorical missing values filled with mode.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized key features like Loan Amount, Education, and Income.  
   - Identified class distribution and feature trends.

3. **Data Preprocessing**  
   - Label Encoding for categorical variables.  
   - Converted ‘3+’ in Dependents to numerical 3.  
   - Separated features and target variable.

4. **Modeling**  
   - Split data into training and testing sets.  
   - Trained a Logistic Regression model to predict loan approval status.  

5. **Evaluation**  
   - Evaluated model performance using accuracy and confusion matrix.

## Results
- The Logistic Regression model achieved an accuracy of **78%** on the test set.
- Confusion matrix visualized to highlight correct and incorrect predictions.

## Key Insights
- Higher education and credit history tend to correlate with increased loan approval rates.
- Applicant Income and Loan Amount have typical right-skewed distributions.
- Logistic Regression provides a baseline model for credit risk prediction, which can be further improved with advanced models or feature engineering.

## Conclusion
This project showcases a complete workflow for credit risk prediction: from data cleaning and EDA to model building and evaluation. It demonstrates how machine learning can support financial institutions in making data-driven decisions for loan approvals.

## References
- Dataset: [Kaggle Loan Prediction Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)
- pandas: [pandas Documentation](https://pandas.pydata.org/docs/)
- seaborn: [seaborn Documentation](https://seaborn.pydata.org/)
- matplotlib: [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- scikit-learn: [scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
