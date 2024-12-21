# Entry_Statistical_Measures_EDA
Project Overview This project involves examining and analyzing the property prices in Bangalore using house_price.csv. The goal is to conduct an exploratory data analysis (EDA), identify and handle outliers using multiple techniques, and assess the correlation and distribution of features in the dataset. This process helps in understanding the dataset better and preparing it for further machine learning applications.

Objective The objective of this project is to:

Perform basic exploratory data analysis on property price data. Detect and handle outliers using various methods. Analyze the distribution of the 'price per square feet' column. Check the correlation among numerical columns.

Dataset Name: house_price.csv Description: Contains property prices and related features for properties in Bangalore.

Key Tasks and Steps

1. Exploratory Data Analysis (EDA) Perform basic EDA to understand the dataset's structure, feature distributions, and unique values.

2. Outlier Detection and Handling

Methods Used: Mean and Standard Deviation Percentile Method (cut-offs: < 5% and > 95%) Interquartile Range (IQR) Z-score Outlier Removal Techniques: Trimming Capping Imputation (using mean or median) Goal: Determine the best method for handling outliers.

3. Box Plot for Outlier Analysis Create a box plot to visually assess which outlier detection method is most effective for this dataset.

4. Normality Check for Price per Square Feet Plot a histogram (histplot) for the 'price per sqft' column. Check skewness and kurtosis to analyze the normality of data distribution. Apply transformations if necessary to improve normality.

5. Correlation Analysis Calculate and analyze the correlation between numerical columns in the dataset. Visualize the correlation matrix with a heatmap.

6. Scatter Plot for Variable Correlation Create scatter plots between different variables to observe relationships and correlations.
