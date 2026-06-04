# student-academic-performance-analysis
Machine learning analysis of student academic performance using Python, Scikit-Learn, and statistical modeling
Overview

This project investigates how learning methods and student behaviors impact academic performance. Using a dataset of high school students, exploratory data analysis and machine learning techniques were applied to determine whether factors such as study hours, attendance, smartphone usage, and learning method can predict exam scores.

Research Question

Can student academic performance be predicted using behavioral and instructional variables such as:

Study Hours
Attendance
Smartphone Usage
Learning Method (Online, Offline, Mixed)
Grade Level
Favorite Subject

Dataset
Source: Kaggle Student Academic Performance Dataset
Size: [number of records]
Features:
Study Hours
Attendance
Exam Score
Learning Method
Grade Level
Favorite Subject
Smartphone Usage

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook

Methodology
Data Preprocessing
Missing value analysis
Categorical variable encoding
Outlier examination
Feature preparation
Exploratory Data Analysis
Descriptive statistics
Learning method comparison
Correlation analysis
Scatterplots and visualizations
Machine Learning Models
Multiple Linear Regression
Decision Tree Regression
Random Forest Regression

Results
Model	RMSE	R²
Multiple Linear Regression	18.63	0.067
Decision Tree Regression	20.15	-0.365
Random Forest Regression	18.03	-0.092

Key Findings
Study hours showed the strongest positive relationship with exam scores.
Learning method alone was not a strong predictor of academic performance.
Smartphone usage demonstrated only a weak relationship with exam outcomes.
More advanced machine learning models did not significantly improve predictive performance.
Academic achievement appears to be influenced by additional factors not present in the dataset.
Future Improvements

Potential variables for future analysis:

Student motivation
Socioeconomic status
Prior academic performance
Teacher quality
Family support systems

Authors-
Avneet Kaur and
Team Members
