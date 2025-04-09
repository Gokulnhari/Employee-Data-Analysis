# Employee Data Analysis Project


## Project Overview

This project analyzes a dataset from ABC Company containing 458 rows and 9 columns. The objective is to generate a comprehensive report detailing insights about employees across various teams. The project encompasses data preprocessing, detailed analysis, and graphical representation of findings.

## Dataset Description

The dataset includes the following columns:

- **Name**: Employee's name
- **Team**: The team to which the employee belongs
- **Number**: Employee's jersey or unique identifier number
- **Position**: Job role or position in the company
- **Age**: Employee's age
- **Height**: Employee's height (corrected during preprocessing)
- **Weight**: Employee's weight
- **College**: The college from which the employee graduated (optional in analysis)
- **Salary**: Employee's salary

## Project Steps

### 1. Preprocessing

- **Height Correction**: Addressed inconsistencies in the Height column by replacing values with random numbers between 150 and 180 cm.
- **Salary Imputation**: Handled missing values in the Salary column by imputing the mean value.
- **Duplicate Removal**: Eliminated duplicate records to ensure data integrity.

### 2. Analysis Tasks

- **Team Distribution**: Calculated the number and percentage of employees in each team.
- **Position Analysis**: Segregated employees based on their positions to assess demand for specific roles.
- **Age Group Trends**: Identified predominant age groups among employees.
- **Salary Insights**: Determined which teams and positions incur the highest salary expenditures.
- **Age and Salary Correlation**: Analyzed the relationship between age and salary using correlation and regression techniques.

### 3. Visualizations

- **Bar Charts and Pie Charts**: Illustrated team distribution and position analysis.
- **Heatmaps**: Showcased correlations between numerical variables.
- **Grouped Bar Plots**: Compared salary expenditures across teams and positions.
- **Scatter Plots**: Visualized correlations between age and salary.

## Key Insights

- **Balanced Workforce**: Teams are evenly distributed, with certain teams slightly overrepresented.
- **Critical Roles**: Positions such as SG and PF are the most common, reflecting their strategic importance.
- **Young Workforce**: The majority of employees fall within the 26-35 age group, followed by those aged 18-25.
- **Salary Trends**: Positions like C and PG command the highest salaries, emphasizing their pivotal roles.
- **Performance Pay Balance**: While age shows a slight correlation with salary, exceptional young talent often earns competitive pay.

## How to Use This Repository

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/gokulnhari/Employee-Data-analysis.git

