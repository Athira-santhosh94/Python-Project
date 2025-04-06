#  Python Data Analysis Project - Employee Dataset
This project focuses on **analyzing and visualizing** an employee dataset using Python libraries like 'pandas','NumPy', 'matplotlib', and 'seaborn'.

## Dataset
Dataset: https://docs.google.com/spreadsheets/d/1VP9BE_eI2yl6uUHSm4mGiiwjRdoqCqnkcIjsv5Q2ex4/edit?usp=share_link 

## Overview
The dataset contains employee information such as age, salary, team, position, and height.

## Preprocessing Steps
* **Standardized column names**: All column names in the dataset were stripped of extra whitespace and converted to lowercase for consistency.
* **Height column generation**: The dataset did not contain a valid 'height' column, so a synthetic one was created using NumPy with random integers between 150 and 180 cm.
* **Age group classification**: The 'age' column was grouped into ranges (18–25, 26–35, etc.) to categorize employees into meaningful age groups.
* **Missing column checks**: Before each analysis, the presence of necessary columns was checked to ensure robustness of the code.

### Data Analysis and Visualization
* Data preprocessing
* Distribution analysis across teams(Bar Chart)
* Distribution analysis across positions(Bar Chart)
* Identifying predominent age groups (Bar Chart)
* Salary expenditure analysis by team and postions(Side-by-Side bar charts)
* Exploring correlation between age and salary(Scatter plot)
* 
## Insights(Data story)
* Most employees are in the team with the highest count, forming a major part of the workforce.
* The most common job position appears in large numbers.
* The age group with the highest representation indicates the company’s workforce majority.
* Teams and positions with the highest salary expenses are identified.
* Visual analysis explores whether there is a correlation between age and salary.
## Requirements
- Python 
- pandas
- numpy
- matplotlib
- seaborn

## Screenshots of Visualizations
1. ![Team Distribution Graph](https://github.com/Athira-santhosh94/Python-Project/blob/main/Distribution%20across%20teams.jpg)
2. ![Employee distribution by position](https://github.com/Athira-santhosh94/Python-Project/blob/main/Employee%20count%20by%20position.jpg)
3. ![Employees predominant age group](https://github.com/Athira-santhosh94/Python-Project/blob/main/Age%20group%20categorization.jpg)
4. ![Total salary expenditure by team and position](https://github.com/Athira-santhosh94/Python-Project/blob/main/Salary%20expenditure%20by%20team%20and%20position.jpg)
5. ![Correlation between age and salary](https://github.com/Athira-santhosh94/Python-Project/blob/main/Correlation%20between%20Age%20and%20Salary.jpg)
