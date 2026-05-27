\# Telecom Churn EDA Project



\## Project Overview



This project performs Exploratory Data Analysis (EDA) on a telecom customer churn dataset containing customer demographic details, telecom usage behavior, and churn information from major Indian telecom providers including Airtel, Reliance Jio, Vodafone, and BSNL.



The objective of this project is to analyze customer behavior, identify churn-related patterns, perform statistical analysis, engineer useful features, and generate business insights through data visualization and preprocessing techniques.



\---



\# Dataset Information



\- Total Records Used: 20,000

\- Original Dataset Size: 243,553 rows

\- Domain: Telecom

\- Target Variable: `churn`



\### Key Features



\- customer\_id

\- telecom\_partner

\- gender

\- age

\- state

\- city

\- estimated\_salary

\- calls\_made

\- sms\_sent

\- data\_used

\- churn



\---



\# Project Workflow



\## Day 1

\- Project setup

\- Dataset loading

\- Initial data profiling

\- Missing value analysis

\- Datatype identification



\## Day 2

\- Data cleaning

\- Datatype fixing

\- Standardization of categorical variables

\- Missing value handling

\- Duplicate removal

\- Outlier analysis



\## Day 3

\- Univariate analysis

\- Bivariate analysis

\- Correlation analysis

\- Segment analysis



\## Day 4

\- Statistical testing

\- Time-based EDA

\- Feature engineering

\- Final insights generation



\---



\# Exploratory Data Analysis



\## Univariate Analysis

Performed:

\- Histograms

\- KDE plots

\- Boxplots

\- Countplots



\## Bivariate Analysis

Performed:

\- Scatterplots

\- Correlation heatmaps

\- Boxplots

\- Grouped barplots



\## Statistical Tests

Conducted:

\- T-Test

\- ANOVA

\- Chi-Square Test



\---



\# Feature Engineering



Created engineered features including:

\- age\_group

\- usage\_segment

\- customer\_tenure\_days

\- salary\_category

\- total\_activity



\---





\# Top 10 Insights



1\. Customers belong to different age groups with relatively balanced distribution.

2\. Telecom partner names had inconsistent formatting and were standardized during data cleaning.

3\. Salary and some telecom activity columns contained noticeable outliers and skewed distributions.

4\. Calls made and mobile data usage showed a weak relationship.

5\. Data usage patterns were relatively similar across telecom providers.

6\. Gender showed slight variation in customer churn behavior.

7\. Customers displayed different telecom usage behaviors across calls, SMS, and data services.

8\. Customer registrations varied across different months.

9\. Feature engineering helped improve customer segmentation and analysis.

10\. Data cleaning and preprocessing improved the overall quality and consistency of the dataset.

\---



\# Segment Findings





\- Middle-aged customers were more common in the dataset.





\- Customer churn showed slight differences across customer groups.





\- Telecom providers showed small differences in customer usage patterns.





\- High-income customers showed different telecom usage behaviors.




\- Some low-activity customers appeared more likely to churn.





\- Usage behavior differed across age groups and telecom providers.




---



\# Data Quality Issues Identified



\- Inconsistent capitalization in categorical variables

\- Mixed date formats

\- Duplicate records

\- Missing values

\- Numerical outliers

\- Datatype inconsistencies



\---



\# Tools \& Libraries Used



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- SciPy





\---



\# Final Outcome



This project demonstrates a complete end-to-end EDA workflow including data cleaning, preprocessing, visualization, statistical analysis, feature engineering, and business insight generation for telecom churn analysis.

