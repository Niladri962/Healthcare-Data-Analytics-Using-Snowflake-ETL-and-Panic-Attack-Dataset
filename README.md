## **<h1 align="center">Snowflake ETL Pipeline for Panic Attack Dataset</h1>**

This project demonstrates an end-to-end ETL pipeline built using Snowflake to process and analyze a panic attack dataset stored in a CSV file. The pipeline ingests raw data, performs transformations, and loads the cleaned dataset into Snowflake tables for further analysis and reporting.


Project Overview

The dataset contains information related to panic attacks including demographic details, health indicators, lifestyle habits, and symptoms. Using Snowflake, the project implements a scalable ETL workflow to transform raw CSV data into a structured format suitable for analytics.



Dataset

The dataset includes attributes such as:

  1. Age

  2. Gender

  3. Panic attack frequency

  4. Duration of attacks

  5. Triggers

  6. Heart rate and physical symptoms

  7. Lifestyle factors (sleep, caffeine, alcohol, exercise, smoking)

  8. Medical history and medication

  9. Therapy status

  10. Panic score




ETL Workflow

  1. Extract

     a) Load the CSV dataset into Snowflake using stages or Snowflake data loading utilities.

  2. Transform

     a) Clean missing or inconsistent values

     b) Standardize categorical fields

     c) Perform data validation and formatting

     d) Prepare analytical fields

  3. Load

     a) Store the transformed dataset into Snowflake tables

     b) Enable querying and analytics using Snowflake SQL


     

Technologies Used

  1. Snowflake – Cloud data warehouse for ETL and analytics

  2. SQL – Data transformation and querying

  3. CSV Dataset – Source data

  4. GitHub – Version control and project documentation





Use Cases

  a) Health data analysis

  b) Panic attack pattern identification

  c) Lifestyle factor correlation with panic scores

  d) Data warehousing and ETL practice with Snowflake
