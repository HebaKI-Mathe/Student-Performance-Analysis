# Student Performance Analysis & Classification

## Overview
This project focuses on analyzing student performance data to identify key factors influencing academic pass/fail outcomes and predicting student success using Logistic Regression.

## Dataset
The dataset contains **1,020 student records** with **9 features**, including:
* Academic metrics: `gpa_prev`, `attendance_rate`, `hours_study`.
* Behavioral factors: `sleep_hours`, `social_media_hours`.
* Demographic & Categorical variables: `gender`, `city`.
* Target variable: `passed` (1 = Pass, 0 = Fail).

## Key Highlights
* **Class Imbalance Handling:** Addressed the 92.75% pass vs. 7.25% fail distribution using SMOTE.
* **Data Preprocessing:** Handled missing values (~5%) and scaled numerical features.
* **Exploratory Data Analysis (EDA):** Visualized distributions and detected key outliers in study and social media hours.

## Technologies Used
* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-Learn
* Imbalanced-Learn (SMOTE)
