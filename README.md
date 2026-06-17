# Project 2: Exploratory Data Analysis (EDA)

## Overview

This project focuses on Exploratory Data Analysis (EDA) of an E-Commerce dataset as part of the Data Analytics Internship at Decodelabs.

## Dataset Information

- Total Records: 1,200
- Total Columns: 14
- Dataset Type: E-Commerce Sales Data

## Features

- OrderID
- Date
- CustomerID
- Product
- Quantity
- UnitPrice
- ShippingAddress
- PaymentMethod
- OrderStatus
- TrackingNumber
- ItemsInCart
- CouponCode
- ReferralSource
- TotalPrice

## Project Objectives

- Perform Exploratory Data Analysis (EDA)
- Understand data distribution and trends
- Handle missing values
- Check duplicate records
- Generate descriptive statistics
- Detect outliers
- Analyze customer purchasing patterns
- Identify correlations between variables

## Data Cleaning Process

### Missing Value Handling

- Identified missing values in the CouponCode column
- Replaced missing values with "Unknown"

### Duplicate Check

- Checked for duplicate records
- No duplicate records were found

### Data Validation

- Verified data types and dataset structure
- Confirmed data consistency before analysis

## Statistical Analysis

The following descriptive statistics were calculated:

- Mean
- Median
- Count
- Minimum Value
- Maximum Value
- Standard Deviation
- Quartiles (Q1, Q2, Q3)

## Key Statistics

- Average Quantity: 2.95
- Average Unit Price: 356.41
- Average Items in Cart: 5.49
- Average Total Price: 1053.97

## Visualizations Performed

### Distribution Analysis

Histogram was used to analyze the distribution of TotalPrice.

### Outlier Detection

Boxplot was used to identify extreme values and outliers in TotalPrice.

### Payment Method Analysis

Bar chart was used to analyze customer payment preferences.

### Order Status Analysis

Bar chart was used to understand order completion and delivery trends.

### Correlation Analysis

Heatmap was created to identify relationships among:

- Quantity
- UnitPrice
- ItemsInCart
- TotalPrice

## Key Findings

- The dataset contains 1,200 valid records
- Missing values were successfully handled
- No duplicate records were found
- TotalPrice distribution is positively skewed
- Several high-value transactions were identified as outliers
- UnitPrice shows a strong positive correlation with TotalPrice
- Quantity and ItemsInCart positively influence TotalPrice
- Payment methods are relatively balanced across customers

## Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

 ## LinkedIn Post

LinkedIn Post:
https://www.linkedin.com/posts/sriharini-k-8ab285359_dataanalytics-eda-python-activity-7471943464880889856-Jrc2?utm_source=social_share_send&utm_medium=android_app&rcm=ACoAAFk1FsMByTf3ioE0ky4pEs0jH6CH-7d9mcM&utm_campaign=copy_link

## Conclusion

Exploratory Data Analysis was successfully performed on the E-Commerce dataset. Data quality checks, descriptive statistics, visualization techniques, and correlation analysis were used to uncover valuable insights. The project demonstrates how EDA helps transform raw data into meaningful business information for better decision-making.

## Author
SriHarini  K

Data Analytics Intern – Decodelabs
