📈 Sales Prediction using Machine Learning
📌 Project Overview

Advertising plays a crucial role in driving product sales. Companies invest in multiple marketing channels such as TV, Radio, and Newspaper, but understanding which channel contributes most to sales is essential for maximizing return on investment (ROI).

This project builds machine learning models to predict product sales based on advertising expenditure across different media channels.

🎯 Problem Statement

The objective of this project is to develop a regression model that predicts product sales based on advertising budgets allocated to:

TV

Radio

Newspaper

Since sales are continuous values, this is a regression problem.

📊 Dataset Description

The dataset contains 200 observations and 4 columns:

TV – Advertising budget spent on TV (in thousands of dollars)

Radio – Advertising budget spent on Radio

Newspaper – Advertising budget spent on Newspaper

Sales – Sales generated (in thousands of units) → Target variable

The dataset contains no missing values.

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🤖 Models Implemented

Linear Regression

Random Forest Regressor

📈 Model Evaluation Metrics

The following regression metrics were used:

R² Score

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)
🔍 Feature Importance

Feature importance analysis showed:

TV advertising has the highest impact on sales

Radio advertising has moderate impact

Newspaper advertising has minimal impact

This suggests businesses should prioritize TV and Radio marketing channels for higher sales impact.

🧠 Key Learnings

Difference between regression and classification

Model comparison

Feature importance interpretation

Importance of R² score

End-to-end machine learning workflow

🚀 Conclusion

The Random Forest model achieved an R² score of approximately 0.95, meaning it explains 95% of the variance in sales. The model successfully predicts sales based on advertising budgets and provides insights into which marketing channels contribute most effectively to revenue growth.

This project demonstrates practical application of machine learning for business decision-making.
