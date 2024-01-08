# YAN-WU_22082478
Project Overview: E-Commerce Customer Behaviour Analysis

Objective:
The primary goal of this project is to conduct a comprehensive analysis of customer behavior on an e-commerce platform, utilizing a dataset that captures various customer attributes and purchase history. The insights derived from this analysis will aid in making data-driven decisions to enhance the overall customer experience and inform strategic business initiatives.
By employing advanced analytics techniques, the analysis aims to achieve the following objectives:
Identify Key Drivers:
Determine the most influential factors that contribute to variations in total spending among customers. This involves a detailed examination of individual features such as membership type, average ratings, and geographic locations.
Segmentation Insights:
Gain a nuanced understanding of customer segments based on demographics, location, and other attributes. This segmentation will provide a foundation for targeted marketing strategies and personalized approaches.
Formulate Actionable Strategies:
Translate the insights into actionable business strategies. This includes developing targeted promotions, loyalty programs, and geographically tailored marketing initiatives to optimize customer engagement and increase overall spending.
Enhance Customer Satisfaction:
Explore the correlation between customer satisfaction, as reflected in average ratings, and spending behavior. Identify areas for improvement and formulate strategies to enhance customer satisfaction, leading to increased spending.
Optimize Geographic Targeting:
Leverage geographic insights to optimize marketing efforts. Tailor promotional campaigns and product recommendations based on regional preferences to maximize customer engagement and spending.
Encourage Repeat Purchases:
Understand the impact of temporal factors, such as the days since the last purchase, on customer spending. Develop strategies to encourage regular purchases and implement retention initiatives for customers with longer intervals between transactions.
Dataset Overview:
Dataset Description: E-commerce Customer Behavior
Dataset Structure:
Customer ID (Numeric)
Gender (Categorical: Male, Female)
Age (Numeric)
Location (Categorical: City names)
Membership Type (Categorical: Gold, Silver, Bronze)
Total Spend (Numeric)
Items Purchased (Numeric)
Average Rating (Numeric: 0 to 5, with decimals)
Discount Applied (Boolean: True, False)
Days Since Last Purchase (Numeric)
Satisfaction Level (Categorical: Satisfied, Neutral, Unsatisfied)
Data Exploration and Preparation:
Data Source:
https://www.kaggle.com/datasets/uom190346a/e-commerce-customer-behavior-dataset
Data Cleaning and Enrichment:
Used Talend Data Preparation for initial data handling, including renaming columns and exploring data quality.
Added relevant attributes such as 'Age Group' for segmentation based on age.
Missing Value Handling:
Identified and located missing values, applying Impute Based on Business Logic strategy for satisfaction level.
Variable Roles Specification
In SAS Enterprise Miner, specified variable roles: 'Customer ID' as 'Input,' 'Gender' and other features as 'Input,' and 'Total Spend' as the 'Target' variable.
Exploratory Data Analysis (EDA)
Simple EDA:
Conducted exploratory data analysis to gain initial insights into the dataset's characteristics.
Explored individual columns and relationships between them.
Advanced EDA:

Utilized SAS Enterprise Miner for advanced EDA, including correlation analysis, univariate and bivariate analysis, and multivariate analysis.
Modeling and Analysis
Decision Tree Analysis
Created a decision tree model in SAS Enterprise Miner to analyze customer behavior, with 'Total Spend' as the target variable.
Ensemble Methods - Random Forest
Applied Bagging and Boosting using the Random Forest algorithm in SAS Enterprise Miner.
Key Use Cases:
Customer Segmentation:
Analyzed and categorized customers based on demographics, spending habits, and satisfaction levels.
Promotion Strategy:
Assessed the impact of discounts on customer spending and tailored promotional strategies accordingly.
Retention Strategies:
Developed targeted retention strategies by understanding the time gap since the last purchase.
Business Recommendations:
Target high-spending customer segments for personalized marketing campaigns.
Optimize discount strategies based on the analysis of their impact on customer spending.
Implement retention strategies tailored to customer behavior patterns.
Deliverables:
Detailed report documenting each step of the analysis with rationales and challenges faced.
Analysis of decision tree and ensemble methods, providing insights into customer behavior for informed business strategies.

In the context of E-Commerce Customer Behaviour Analysis, SAS Enterprise Miner and Talend Data Preparation play distinct yet complementary roles.

SAS Enterprise Miner
Role:
Advanced Data Analysis:

SAS Enterprise Miner is employed for advanced exploratory data analysis (EDA), statistical modeling, and machine learning.
It facilitates the creation of decision tree models, ensemble methods like Random Forests, and gradient boosting for predictive analytics.
Model Deployment:

SAS Enterprise Miner allows the deployment of machine learning models, making it valuable for integrating analytical results into business processes.
Variable Role Specification:

SAS Enterprise Miner assists in specifying variable roles, crucial for modeling. It allows the definition of input, target, and rejected variables, guiding the algorithm on how to use each feature.
Ensemble Methods:

SAS Enterprise Miner supports ensemble methods like Random Forests, contributing to improved model accuracy.
Process:
Data Import and Preprocessing:

Import the dataset into SAS Enterprise Miner, handle missing values, and specify variable roles.
Decision Tree Analysis:

Create a decision tree model to analyze customer behavior.
Ensemble Methods:

Apply Bagging and Boosting, using Random Forests as a Bagging example.

Talend Data Preparation
Role:
Data Cleaning and Transformation:

Talend Data Preparation is employed for data cleaning, transformation, and initial exploratory analysis.
It assists in handling missing values, identifying data quality issues, and preparing the dataset for further analysis.
Feature Engineering:

Talend allows the creation of new features and the transformation of existing ones, contributing to a more informative dataset.
Process:
Initial Data Handling:

Utilize Talend for initial data handling, including renaming columns, exploring data quality, and locating missing values.
Data Cleaning and Transformation:

Use Talend Data Preparation to clean and transform the dataset, addressing issues like missing values and ensuring data quality.
Variable Inspection:

Talend aids in the inspection of each feature, allowing for a detailed understanding of the dataset and its characteristics.
In summary, Talend Data Preparation serves as a valuable tool for the initial stages of data handling and exploration, ensuring the dataset is well-prepared for advanced analysis in SAS Enterprise Miner. Together, they form a comprehensive approach to E-Commerce Customer Behaviour Analysis. Talend addresses the initial data preprocessing steps, while SAS Enterprise Miner takes over for advanced modeling and analysis.
