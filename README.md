# ETL-Project-Kaggle-Data-Engineering 

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Cleaning and Transformation Tasks](#data-cleaning-and-transformation-tasks)
- [SQL Analysis](#SQL-Analysis)
- [How to Run the Project](#how-to-run-the-project)
- [Contributing](#contributing)

## Introduction

This project demonstrates a simple ETL (Extract, Transform, Load) process using Python and SQL. The main objective is to extract a dataset from Kaggle, transform it using Python and Pandas, and load it into an SQL database for further analysis.

## Project Overview
![Alt Text](ELT.png) <br>

### Steps Involved:
- **Extract**: Download the Netflix Movies and TV Shows dataset using Python.
  
- **Load**: Load the raw data into the Raw Data Layer using SQL.
  
- **Transform**: Perform data cleaning, modeling, and transformations on the raw data. Load the transformed data into the Final Staging Layer.
  
- **Analyze**: Conduct data analysis using SQL to answer 5 specific questions.

## Dataset

This dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

## Data Cleaning and Transformation Tasks

- **Handling Foreign Characters**: Ensure all foreign characters in the dataset are correctly encoded and standardized.

- **Removing Duplicates**: Identify and remove any duplicate entries to ensure data integrity.
  
- **Data Type Conversion**: Convert data types as necessary for accurate data analysis.
  
- **Identify and Populate Missing Values**: Detect missing values and use appropriate methods to populate them.
  
- **New Dimension Table for Countries**: Create a new dimension table for countries and list relevant data for comprehensive analysis.

## SQL Analysis

Using the transformed data in the Final Staging Layer, perform SQL queries to answer the following five questions:

- **Question 1**: For each director count the no of movies and tv shows created by them in separate columns 
for directors who have created tv shows and movies both.

- **Question 2**: Which country has highest number of comedy movies.
  
- **Question 3**: For each year (as per date added to netflix), which director has maximum number of movies released.
  
- **Question 4**: What is average duration of movies in each genre.
  
- **Question 5**: ind the list of directors who have created horror and comedy movies both.

## How to Run the Project

 **1. Prerequisites**:
- Ensure you have Python and a SQL database installed.
- Install required Python libraries using pip install -r requirements.txt.

**2. Download Dataset**: 
- Use the provided Python script to download the dataset.

**3. Load Data**:
- Load the raw data into the SQL database.
  
**4. Transform Data**:
- Execute SQL scripts for data cleaning and transformation.

**5. Analyze Data**: 
- Run the SQL queries to answer the specified questions.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure they work as expected.
4. Commit your changes and create a pull request.

