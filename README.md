# Task1-Data-Cleaning
Data Cleaning and Preprocessing of Customer Personality Dataset

Objective:
This task involves cleaning and preprocessing the Customer Personality Analysis dataset. The main goal is to prepare the raw data for analysis by handling missing values, standardizing formats, and ensuring data consistency.

Files Included:
- data_cleaning.ipynb : Jupyter notebook containing the code and explanations for each data cleaning step.
- cleaned_customer_personality.csv : Final cleaned dataset after preprocessing.
- README.md : Description of the task and steps performed.

Tools Used:
- Google Colab
- Python (Pandas library)

Steps Performed:
1. Loaded the dataset and displayed the initial shape and structure.
2. Identified missing values using isnull() and filled missing income values with the mean.
3. Removed duplicate rows using drop_duplicates().
4. Cleaned and standardized categorical text columns such as Education and Marital_Status.
5. Converted the Dt_Customer column to proper datetime format.
6. Renamed all column headers to lowercase and replaced spaces with underscores for uniformity.
7. Ensured correct data types for numerical and date columns.

Dataset Source:
Customer Personality Analysis dataset from Kaggle:
https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis
