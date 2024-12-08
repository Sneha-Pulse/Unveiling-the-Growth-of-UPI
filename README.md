# Unveiling-the-Growth-of-UPI
A Data-Driven Analysis of India’s Digital Payment Revolution

Introduction

Unified Payments Interface (UPI) has revolutionized digital payments in India, making it one of the most popular and widely used payment systems in the country. With millions of transactions happening every day, analyzing UPI transaction data can provide valuable insights into consumer behavior and the overall performance of different payment platforms.

Here, we'll dive deep into UPI transaction data from 2021, using advanced data analytics and machine learning techniques to uncover trends, predict high transaction volumes, and evaluate the performance of different models. We'll walk through each step of the process, from exploratory data analysis (EDA) to building and comparing machine learning models, all while visualizing our findings for better understanding.

Exploratory Data Analysis (EDA)

The first step in any data analysis project is to understand the data we're working with. For this analysis, we're using a dataset that contains UPI transaction information for various banks and payment apps in India for the year 2021.

The dataset includes the following columns:

UPI Banks: The name of the bank or payment app.
Volume (Mn) By Customers: The transaction volume in millions for each platform.
Value (Cr) by Customers: The transaction value in crores for each platform.
Volume (Mn): Another measure of transaction volume, possibly representing a different user segment.
Value (Cr): Another measure of transaction value.
Month: The month of the transaction.
Year: The year of the transaction.
To kick things off, we’ll start by checking for any missing values and analyzing the summary statistics to get an overview of the dataset. Thankfully, the data was clean with no missing values, allowing us to proceed with confidence.

Visualizing Data Distribution

Visualizing the distribution of transaction volumes we get to understand the spread and also helps identify any potential outliers. A correlation matrix will also help identify relationships between different features, revealing that transaction volume and value are strongly correlated, as expected.

To add more depth to the analysis, a binary target variable was added, High_Volume, based on whether the transaction volume for a platform exceeded the median volume. This new variable would later serve as the target for the machine learning models.


For more deatiled analysis, read https://medium.com/@sneha.p_30136/unveiling-the-growth-of-upi-a-data-driven-analysis-of-indias-digital-payment-revolution-e47b2705b3ff
