# IBM Data Analysis with Python and Data Visualization with Python - Practice Projects
This repository contains practice projects completed as part of the IBM Data Analysis with Python and Data Visualization with Python courses. Both courses provide hands-on experience in data analysis and visualization using popular Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, Plotly, and Dash.

## Overview
These projects highlight my ability to:
- **Data Analysis**: Import, clean, and preprocess data, perform exploratory data analysis (EDA), and develop and evaluate regression models.
- **Data Visualization**: Create and customize various types of plots, including line, scatter, bar, and pie charts. Implement interactive dashboards using Plotly and Dash to create compelling data stories.

For more details on the courses, visit the [IBM Data Analysis with Python course](https://www.coursera.org/learn/data-analysis-with-python) and [Data Visualization with Python](https://www.coursera.org/learn/python-for-data-visualization).

## Projects

### Project 1: Insurance Cost Analysis
**Description**: In this project, I performed analytics operations on an insurance database that uses the following parameters:

| Parameter        | Description                               | Content Type           |
|------------------|-------------------------------------------|------------------------|
| age              | Age in years                              | Integer                |
| gender           | Male or Female                            | Integer (1 or 2)       |
| bmi              | Body mass index                           | Float                  |
| no_of_children   | Number of children                        | Integer                |
| smoker           | Whether smoker or not                     | Integer (0 or 1)       |
| region           | Which US region - NW, NE, SW, SE          | Integer (1, 2, 3, or 4)|
| charges          | Annual Insurance charges in USD           | Float                  |

**Objectives**:
- Load the data as a pandas dataframe
- Clean the data, handling missing values
- Perform exploratory data analysis (EDA) to identify attributes most affecting the charges
- Develop single-variable and multi-variable Linear Regression models to predict the charges
- Use Ridge Regression to refine the performance of the linear regression models

**Libraries Used**:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Project 2: Add Interactivity with Dash: User Input and Callbacks
**Description**:
In this project, I explored how to add multiple graphs to a Dash dashboard and handle multiple outputs using Dash Callbacks. This project demonstrated how to create dynamic and interactive data visualizations by allowing the user to interact with multiple components simultaneously.

**Objectives**:
- Work with Dash callbacks to make the dashboard interactive.
- Capture user input and use it to update the visualizations.
- Learn how to add multiple graphs to a Dash dashboard.

**Dataset Used**:
Airline Reporting Carrier On-Time Performance dataset from Data Asset eXchange.

**Libraries Used**:
- Pandas
- Plotly
- Dash
