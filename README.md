# AMCAT-EDA
Project Overview

This project involves performing Exploratory Data Analysis (EDA) on a given dataset, with the objective of analyzing the "Salary" as the target variable. The dataset contains information about various attributes related to employees, such as educational background, job designation, gender, and salary. The goal is to uncover insights, detect patterns, and explore relationships between different features using visualizations and statistical methods.

Project Steps

1. Introduction

Detailed description of the dataset, including column names and types.

Objective of the analysis: Understanding the factors that influence Salary.


2. Data Import and Exploration

Imported the dataset and displayed the first few rows to understand the data structure.

Displayed the shape and description of the data to get insights into the numerical features.


3. Univariate Analysis

Generated histograms and boxplots for numerical columns (e.g., Salary, collegeGPA) to visualize distributions and identify outliers.

Created count plots for categorical variables (e.g., Gender, Designation) to understand their frequency distributions.


4. Bivariate Analysis

Used scatter plots and pair plots to discover relationships between numerical columns (e.g., Salary vs. collegeGPA).

Explored the interaction between categorical and numerical variables using boxplots and barplots (e.g., Salary by Gender, Salary by CollegeTier).

Examined relationships between categorical variables using stacked bar plots (e.g., Gender vs Specialization).


5. Research Questions

Question 1: Tested the claim from a Times of India article that fresh graduates in certain roles (Programming Analyst, Software Engineer, Hardware Engineer, Associate Engineer) earn an average salary of 2.5-3 lakhs.

Question 2: Investigated whether there is a relationship between gender and specialization using a Chi-square test.


6. Conclusion

Summarized the findings from the analysis, including observations from the visualizations and statistical tests.


Project Files

EDA_Project.ipynb: The Jupyter Notebook containing all the code for the EDA.

How to Run the Project

1. Download the dataset from the provided link and place it in the same directory as the Jupyter Notebook.


2. Open the EDA_Project.ipynb file in Jupyter Notebook or JupyterLab.


3. Run each cell step by step to perform the analysis.


4. Review the plots and outputs to understand the data insights.



Key Libraries Used

Pandas: For data manipulation and exploration.

NumPy: For numerical operations.

Seaborn and Matplotlib: For data visualization.

Scipy: For statistical testing (Chi-square test).


Research Question Findings

1. The average salary of fresh graduates in certain roles is compared against the claim that they earn between 2.5-3 lakhs.


2. A Chi-square test was conducted to explore whether the preference for specialization depends on gender, leading to an interpretation of statistical significance.



Conclusion

The EDA revealed significant patterns in the dataset, such as the distribution of salaries across genders and specializations, and relationships between educational background and salary. This project demonstrates the importance of data visualization and statistical analysis in uncovering insights.
