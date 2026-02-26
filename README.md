Problem Statement

Understanding income distribution is important for economic analysis, policy-making, and targeted marketing strategies. However, predicting whether an individual earns above or below a certain income threshold based on demographic and employment attributes can be complex due to multiple influencing factors.

The objective of this project is to develop a Machine Learning classification model that predicts whether an individual’s income exceeds a specified threshold using features such as age, education, occupation, working hours, and marital status. The model aims to assist in demographic income analysis and decision-making processes.


Project Objective

Build a binary classification model using Logistic Regression

Identify key demographic features influencing income level

Evaluate model performance using classification metrics

Interpret model outputs for practical insights




Dataset Description

The dataset contains demographic and employment-related attributes such as:

Age

Workclass

Education

Education Number

Marital Status

Occupation

Relationship

Race

Gender

Capital Gain

Capital Loss

Hours per Week

Native Country



Target Variable:

<=50K → Low Income

>50K → High Income


Project Workflow
1️ Data Preprocessing

Handled missing values

Removed duplicates

Encoded categorical variables

Scaled numerical features (if applied)

2️ Exploratory Data Analysis (EDA)

Analyzed income distribution

Studied relationship between education, occupation, and income

Checked feature correlations

Purpose:

Identify important predictors

Understand demographic patterns

3️ Model Building

Applied Logistic Regression

Performed Train-Test Split

Trained model on training dataset

Generated predictions on test dataset

4️ Model Evaluation

Evaluated using:

Accuracy Score

Confusion Matrix

Precision

Recall

F1-Score

Special attention was given to balancing precision and recall to avoid biased classification.

 Results & Insights

Education level and working hours showed strong influence on income classification.

Logistic Regression provided interpretable decision boundaries.

The model demonstrated stable and reliable classification performance.

 Key Learnings

Handling categorical features using encoding techniques

Understanding logistic regression in binary classification

Importance of evaluation metrics beyond accuracy

Translating demographic data into predictive insights

 Future Improvements

Try ensemble models (Random Forest, Gradient Boosting)

Perform hyperparameter tuning

Apply cross-validation

Address class imbalance using SMOTE

Deploy model using Streamlit

🏁 Conclusion

This project demonstrates the application of Logistic Regression for income classification using demographic and employment data.

The model provides a structured and interpretable approach to predicting income levels, showcasing the practical use of machine learning in socioeconomic data analysis.
