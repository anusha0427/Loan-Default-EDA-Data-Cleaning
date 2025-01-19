
# 

## Project Overview
This project aims to analyze customer churn for a bank's credit card services. The objective is to understand the reasons behind customer churn and prepare data for predictive modeling. By exploring the data, cleaning it, and visualizing key patterns, we can gain valuable insights that could help the bank in its customer retention efforts.

## Problem Statement
The bank is facing an increasing number of customers leaving their credit card services. With a churn rate of **16.07%**, predicting which customers will churn is challenging. The data is imbalanced, with non-churning customers far outnumbering the churning ones, making it harder to build a reliable predictive model.

## Dataset
The dataset consists of 10,000 customer records and 18 features, including:
- **Age**: Age of the customer.
- **Salary**: Annual salary of the customer.
- **Marital Status**: Marital status of the customer (e.g., Married, Single).
- **Credit Card Limit**: Maximum credit card limit assigned to the customer.
- **Credit Card Category**: Type of credit card (e.g., Standard, Premium).
- **Churn**: Whether the customer has churned (0 = No, 1 = Yes).

## Project Steps

### 1. **Exploratory Data Analysis (EDA)**
   The first step of the project is to explore the dataset and understand its structure. This includes:
   - **Data Distribution**: Analyzing the distribution of key numerical features such as age, salary, and credit card limit using histograms and boxplots.
   - **Churn Analysis**: Examining how different features correlate with customer churn, such as whether age, salary, or marital status has a significant impact on churn.
   - **Missing Data**: Identifying if any columns have missing values and deciding how to handle them.
   - **Feature Correlation**: Investigating how features relate to each other and to the target variable (churn). This helps identify potential predictors for churn.

#### Key Visualizations:
- **Count Plot**: To visualize the distribution of customers who have churned vs. those who have not.
- **Histograms**: To show the distribution of numerical variables like age, salary, and credit card limit.
- **Boxplots**: To check for outliers in numerical features.
- **Correlation Heatmap**: To see the relationships between numerical features.

### 2. **Data Cleaning**
   After performing EDA, the next step is data cleaning, which ensures that the dataset is in a format suitable for analysis and modeling:
   - **Handling Missing Data**: If there are any missing values, decide whether to drop them or impute with mean, median, or mode.
   - **Removing Outliers**: Identify and remove any outliers that may skew the analysis, particularly in numerical columns like salary or credit card limit.
   - **Feature Encoding**: Convert categorical variables like marital status and credit card category into numerical representations using one-hot encoding or label encoding.
   - **Data Normalization/Standardization**: If necessary, normalize or standardize numerical features to bring them to a similar scale, which can be important for later analysis or modeling.

## Tools and Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - **Pandas**: For data manipulation and cleaning.
  - **NumPy**: For numerical computations.
  - **Matplotlib / Seaborn**: For data visualization.
  - **Scikit-learn**: For data preprocessing tasks like encoding and imputation.

## Results of EDA and Data Cleaning
- After completing the EDA and data cleaning process, the dataset will be ready for further analysis or predictive modeling. The cleaned data will highlight key patterns and features that influence customer churn.

## Installation and Setup
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/customer-churn-prediction.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the analysis script:
   ```
   python churn_analysis.py
   ```

## Conclusion
This project focuses on understanding customer churn and preparing the dataset for predictive modeling. By cleaning the data and performing exploratory analysis, we can gain valuable insights into customer behavior, which can be used to improve retention strategies.
