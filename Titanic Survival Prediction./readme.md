The Titanic disaster is one of the most well-known tragedies in history. In this project, machine learning models are used to predict whether a passenger survived or not based on various features such as age, gender, ticket class, fare, and more.

This is a classic beginner-level classification problem that demonstrates the complete machine learning workflow.

🎯 Problem Statement

The objective of this project is to build a classification model that predicts whether a passenger survived the Titanic disaster.

Target Variable:

0 → Did Not Survive

1 → Survived

The goal is to analyze passenger data and identify key factors that influenced survival.

📊 Dataset Description

The dataset contains passenger information such as:

PassengerId – Unique ID of passenger

Pclass – Ticket class (1st, 2nd, 3rd)

Name – Passenger name

Sex – Gender

Age – Age of passenger

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Ticket – Ticket number

Fare – Ticket fare

Cabin – Cabin number

Embarked – Port of embarkation

Survived – Target variable (0 or 1)

The dataset required preprocessing including handling missing values and encoding categorical variables.

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🔄 Data Preprocessing

The following preprocessing steps were performed:

Handling missing values (Age, Cabin, Embarked)

Encoding categorical variables (Sex, Embarked)

Dropping irrelevant columns (Name, Ticket, Cabin if necessary)

Train-test split

🤖 Models Implemented

Logistic Regression

Decision Tree Classifier

(Optional: Random Forest Classifier)

📈 Model Evaluation Metrics

The models were evaluated using:

Accuracy

Confusion Matrix

Precision

Recall

F1 Score

📊 Results

The model successfully classified passenger survival with strong accuracy. Feature importance analysis showed that:

Gender (Sex) played a major role in survival

Passenger class (Pclass) significantly affected survival rate

Fare and Age also influenced survival probability

🧠 Key Learnings

Classification problem understanding

Data cleaning and preprocessing

Handling missing values

Feature engineering

Model comparison and evaluation

Interpretation of classification metrics

🚀 Conclusion

The project successfully demonstrates how machine learning can be used to analyze historical data and predict survival outcomes. The results show that socio-economic factors such as ticket class and gender strongly influenced survival during the Titanic disaster.

This project provides a strong foundation in classification modeling and machine learning workflow.
