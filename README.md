# Exploratory-Data-analysis-python-capstone
This repository contains Python code for analyzing the dataset, preprocessing and visualization.


Excel file containing the dataset of ABC company.
Data analysis is done with jupyter notebook containing python code.


This file provide the overview of the project.

Link to the dataset:
https://docs.google.com/spreadsheets/d/1VP9BE_eI2yl6uUHSm4mGiiwjRdoqCqnkcIjsv5Q2ex4/edit?usp=share_link
ANALYSIS:
1.Import all necessary modules:
1.numpy

2.pandas

3.matplotlib

4.seaborn

2.Reading data set:
our dataset is excel,read_excel function used to load the dataset to pandas

3.Data preprocessing:
1.The main goal of data understanding is to gain general insights about of the data.
info(): Utilized the info() method to  print summary of dataset and identify missing values across
the dataset.
fillna(): method to impute missing values

descibe():It provides summary statistics for numerical columns in the DataFrame, such as count,
mean, standard   
deviation,minimum, maximum, and quartiles.

duplicate(): identify and remove any duplicate rows to ensure data integrity and prevent 
based analysis. 

4. Exploratory Data Analysis (EDA)
     Segregate employees based on their positions within the company.
  
     Identify the predominant age group among employees. 
  
    Discover which team and position have the highest salary expenditure.
  
    Investigate if there's any correlation between age and salary, and represent it visually.
6.Data visualization
   Data visualization: Describe the visualizations created to explore relationships and patterns in the data.
   barplot, scatter plots,pie chart,pairplot are used to visualize the my finding effectively.
