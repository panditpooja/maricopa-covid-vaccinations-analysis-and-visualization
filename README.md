# Maricopa County COVID Vaccinations Analysis
## Description
This repository contains an analysis of COVID vaccination rates in Maricopa County, focusing on age groups and temporal trends from June 2021 to February 2022.

## Scenario Questions
Used the dataset to answer the following questions:
1. How do the vaccination totals between age groups compare?
2. How have the average vaccination totals changed over time in Maricopa County?

## Additional Considerations: 
- The dataset contains unnecessary information, so filtering and selection of relevant data points are crucial so I have provided thorough explanations and summaries in my python code and PDF reports with visual plots.
## Project Overview
This project was conducted using Google Colab, an online platform for Jupyter notebooks that offers free GPU and TPU resources, making it ideal for data-intensive tasks and machine learning experiments.
## Project Steps:
1. **Subset Relevant Columns:**
   - Subset the data by columns to choose only those columns which will help in answering the dataset associated questions.
2. **Data Cleaning:**
   - Renaming the column names of the filtered dataframe to improve readibility and understandibility.
   - Understand the total number of rows and columns of the dataset along with the datatypes of each column. Additionally, figure out how many missing values are present so that I can handle them in the filtered dataset.
   - Convert Date Column: Change the datatype of 'StartDate' from 'Object' to 'DateTime' format for proper date handling.
   - Drop the "StartDate" column as it does not contribute for further analysis.
3. **Data Transformation:**
   - Adding a new column "VaccinatedYear" by extracting the "year" value and another column "VaccinatedMonth" by extracting "month" from "StartDate".
4. **Data visualization:**
   - Perform data visualization for each question to understand the trend over time effectively.
5. **Perform Grouping and Aggregation:**
   - Use pandas to group and aggregate data to answer the specific three questions related to the dataset.
8. **Develop pretty and ugly plots**
   - Create pretty and ugly plots that present the findings related to the two specific questions posed by the dataset.

## Expected Output:
1. Generate one pretty and one ugly plot for each question.
2. Prepare final pdf report with relevant visual plots and python code snippet.
