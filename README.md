# Transformation-of-Badly-Structured-Sales-Data

# Introduction

The company is experiencing disparate revenue and order volumes across its three key segments—Consumer, Corporate, and Home Office. Despite the Consumer segment leading in both revenue and order volume, 
and Home Office achieving the highest average order value, total revenue from Home Office remains the lowest. 

## Problem Statement

The current product mix and delivery options may not be optimized for segment-specific needs, potentially limiting growth opportunities. 

There is a critical need to organize the poorly structured dataset to enable effective analysis, drive higher sales and profitability, and ultimately support informed decision-making.

Objectives:

1.  Improve Sales Structure:
    It is imperative to create a better sales structure for the company.
    
2.  Maintain Reporting Structure: Establish a pipeline for maintaining the structure of monthly reports.

3.  Sales Analysis:
    Identify the top-selling segment and best-selling class.

4.  Profit Margin Analysis:
    Determine which class categories and customer segments generate the highest profit margins.
    Analyze the factors contributing to these margins.

5.  Recommendations:
    Provide recommendations for improving income and profitability.

# Project Overview:

## Data Transformation, Cleaning and Pipeline Process.

This project involved a comprehensive ETL (Extract, Transform, Load) process and the construction of a data pipeline entirely in Microsoft Excel.

## ETL Process:

1. Extraction:
   
In a new Excel worksheet, I navigated to the "Data" tab and selected the "Get Data" option.
I extracted data from a Microsoft Excel (.xlsx) file and loaded it into the Excel Power Query Editor to begin the transformation and cleaning process.

2. Transformation:

  A. Normalization:

    a. 	Dataset Duplication: I duplicated the dataset into three separate tables for distinct processing needs.
    b.	Renaming and Cleaning: Each table was renamed, and redundant rows and columns were removed.
    c.	Data Transposition: I transposed the data from Row A1 into Column B2 and set the data type to text, 
            thereby restructuring it into an acceptable format.
    d.	Column Population: Populated the new column with relevant details.
        I.	Header Creation: Created new headers for the entire table.
        II.	Row Deletion: Deleted the first three rows to finalize the normalization process.

B. Data Cleaning:

   Missing Values: Checked for and handled missing values.
   
   Duplicates: Identified and removed duplicate values.
   
   Redundant Data: Removed any remaining redundant columns or rows.

C.  Data Pipeline:

This sequence of data extraction, transformation, and loading in power query effectively creates a data pipeline. The pipeline ensures data flows seamlessly from the source to the cleaned and transformed state, ready for analysis.

3. Loading:
   
Loaded the cleaned and transformed data back into Excel for further analysis and modelling.

# Modelling:

Created Key Performance Indicators (KPIs) and pivot tables in a new sheet.

Ensured accuracy by cross-checking all calculations and cross-referencing relevant pivot tables.


# Dashboard Development:

Designed the dashboard background by clearing all gridlines and inserting necessary buttons.

Populated the dashboard with KPIs and incorporated filters to enhance data analysis.

By following this structured process, the project ensures accurate and efficient data preparation, enabling robust analysis and insightful dashboard reporting.

The chart below displays the poorly structured and raw sales data.

![]()

The chart below illustrates the results of the ETL process.

![]()

The dashboard below presents the results of a thorough Analysis.

![]()
