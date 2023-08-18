## LAB-02

### Introduction

Data mining and preprocessing are essential steps in the data analysis process. This project demonstrates how to handle categorical variables, visualize relationships between variables, and perform statistical tests to gain insights from the data. The code is in Python and utilizes libraries such as Pandas, NumPy, Matplotlib, Seaborn, sklearn, and SciPy.

### Dataset

The dataset used in this project contains information about customer behaviors and preferences related to online shopping. It includes various features such as age, gender, purchase frequency, product ratings, and more. The goal of this project is to explore the relationships between different variables and uncover meaningful insights.

### Preprocessing

The preprocessing steps performed on the dataset include:

1. Binning the 'age' column into age groups (18-25, 26-35, 36-45, 46+).
2. Handling categorical variables using Label Encoding for the 'Gender' and 'Purchase_Frequency' columns.

### Exploratory Data Analysis

The exploratory data analysis process involves the following:

1. Visualizing the distribution of age groups using a bar plot.
2. Creating a pair plot to visualize relationships between necessary variables.
3. Calculating the covariance matrix and visualizing it using a heatmap.
4. Conduct a Chi-squared test to assess the association between gender and purchase frequency.
5. Comparing product ratings for repeat and non-repeat purchases using an independent T-test.
6. Visualizing the comparison of product ratings using box plots.

### Results

The project provides insights into customer behavior, relationships between variables, and the impact of purchase frequency on product ratings. The visualizations and statistical tests help in understanding patterns and making informed decisions.
