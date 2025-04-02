Understanding Social Demographics and Income Levels

Project Overview

This project explores the relationship between social demographics and income levels using the Adult Dataset. The objective is to identify key factors influencing income levels and build predictive models based on demographic variables.

Team Members

Harsh Anadkat

Owais Baig

Rohith Joginapally

Sudindra Karkera

Goals

Analyze the impact of social and demographic variables on income.

Assess the predictive ability of individual attributes on income levels.

Examine the role of education, occupation, race, and gender in income differences.

Investigate the geographic influence on income for predictive modeling.

Methodology

1. Exploratory Data Analysis (EDA)

Data Exploration: Understanding variable distributions, correlations, and trends.

Summary Statistics: Identifying key insights from central tendencies and variations.

Correlation Analysis: Using visual tools like histograms, box plots, and bar charts.

2. Feature Engineering

Handling Missing Values: Replacing missing data and cleaning inconsistencies.

Target Variable Encoding: Converting the income variable into binary (<=50K and >50K).

Scaling and Encoding: Using one-hot encoding and normalization techniques.

3. Machine Learning Models

Algorithms Used:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

Model Evaluation: Performance assessment using accuracy, precision, recall, and F1-score.

Validation Techniques: Cross-validation and train-test split (80%-20%) to prevent overfitting.

Results

Logistic Regression: Performed well for lower-income predictions but struggled with higher incomes.

Decision Tree: Showed similar results to logistic regression, with lower accuracy for higher incomes.

Random Forest: Provided the best overall performance, especially in predicting higher incomes.

Support Vector Machine: Effective for lower incomes but had challenges with higher-income predictions.

Conclusion

Random Forest emerged as the best-performing model, particularly in accurately predicting higher-income levels, which are generally harder to classify.

Files Included

Dataset.csv - Processed dataset used for analysis.

EDA.ipynb - Jupyter Notebook containing data exploration and visualization.

Model_Training.ipynb - Notebook detailing model training and evaluation.

Dashboard_Link - [Insert Link Here]

GitHub Repository - [Insert Link Here]

How to Run the Project

Clone the repository:

git clone [repo_link]

Install dependencies:

pip install -r requirements.txt

Run the Jupyter notebooks for EDA and model training.

Contact

For questions or collaboration, reach out via GitHub or email.

