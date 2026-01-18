# AI-ML--Internship
📊 Task 1: Understanding Dataset & Data Types
📌 Objective

The objective of this task is to understand the structure, data types, and machine learning readiness of two real-world datasets: Titanic Dataset and Students Performance Dataset. This step is crucial before applying any data preprocessing or machine learning algorithms.

🧰 Tools & Technologies

Python

Pandas

NumPy

Jupyter Notebook / Google Colab

📂 Datasets Used
1️⃣ Titanic Dataset

The Titanic dataset contains information about passengers such as age, gender, passenger class, fare, and survival status. Each row represents one passenger, and the dataset is commonly used for classification problems.

2️⃣ Students Performance Dataset

The Students Performance dataset contains academic scores of students along with demographic and educational background details. Each row represents one student, and the dataset is suitable for regression or classification tasks.

🔍 Dataset Understanding Approach

The same analysis steps were applied to both datasets for consistency:

Loaded datasets using Pandas and inspected the first and last few records

Analyzed dataset size to understand the number of samples and features

Used info() to identify data types and missing values

Used describe() to generate statistical summaries for numerical columns

Identified numerical, categorical, ordinal, and binary features manually

Checked unique values in categorical columns to understand data distribution

Identified target variables and input features for machine learning

Evaluated dataset suitability for ML tasks

🧠 Feature Types Identified
Numerical Features

Titanic: Age, Fare, SibSp, Parch

Students: Math Score, Reading Score, Writing Score

Categorical Features

Titanic: Sex, Embarked, Cabin

Students: Gender, Lunch, Race/Ethnicity

Ordinal Features

Titanic: Passenger Class (Pclass)

Students: Parental Level of Education

Binary Features

Titanic: Survived

Students: Test Preparation Course

⚠️ Data Quality Observations
Titanic Dataset

Contains missing values in Age, Cabin, and Embarked columns

Slight class imbalance in the target variable (Survived)

Requires preprocessing such as missing value handling and categorical encoding

Students Performance Dataset

No missing values present

Clean and well-structured dataset

Requires categorical feature encoding

🎯 Target Variables

Titanic Dataset: Survived (Classification Problem)

Students Dataset: Math Score (Regression / Classification Problem)

🤖 Machine Learning Readiness

Both datasets are suitable for machine learning applications:

Titanic dataset is suitable for classification models after preprocessing

Students dataset is suitable for regression or classification models

Both datasets represent real-world problems and support supervised learning

✅ Conclusion

This task helped in understanding dataset structure, feature types, data quality issues, and overall machine learning readiness. Performing this analysis ensures that appropriate preprocessing and modeling decisions can be made in the subsequent stages of the ML pipeline.
