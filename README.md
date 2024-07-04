# Employee and Project Data Analysis and Manipulation in Python

## Overview
This capstone project involves the analysis and manipulation of employee and project data using Python. The primary objective is to create three dataframes from the given datasets, perform various data cleaning, transformation, and analysis tasks, and finally consolidate the results into meaningful insights. The project showcases proficiency in data handling, including filling missing values, splitting columns, joining dataframes, and applying conditional logic for data manipulation.

## Project Tasks

### Data Preparation:
- **Task 1**: Create three dataframes from the given tables and save them as CSV files. 

### Data Cleaning and Transformation:
- **Task 2**: Handle missing values in the cost column of the Project DataFrame by computing and replacing them with a running average using a for loop.
- **Task 3**: Split the name column in the Employee DataFrame into two new columns: First Name and Last Name. Remove the original name column.

### Data Integration:
- **Task 4**: Join all three dataframes (Employee, Seniority Level, and Project) into a single dataframe named Final.

### Data Analysis and Manipulation:
- **Task 5**: Add a new bonus column to the Final dataframe. Assign a 5% bonus concerning project cost only to employees who have finished their projects.
- **Task 6**: Demote the designation level by 1 for employees whose projects have a status of fail. Remove records of employees whose designation level exceeds 4 after demotion.
- **Task 7**: Add titles (Mr. and Mrs.) to the First Name column based on gender and drop the gender column.
- **Task 8**: Promote the designation level by 1 for employees whose age is greater than 29 years using an IF condition.

### Summarization and Filtering:
- **Task 9**: Calculate the total project cost for each employee and save it in a new dataframe named TotalProjCost with columns ID, First Name, and Total Cost.
- **Task 10**: Print the details of employees whose city names contain the letter "o".

## Repository Content:
-  **Employee and Project Data Analysis.ipynb** - IPYNB File - Python file with all the data analysis
-  **Project Details.pdf** - PDF File - Explaining the Problem statements of the project
-  **Project and Employee Tables** - Excel File - Raw data of Projects, Employees and Seniority levels tables

