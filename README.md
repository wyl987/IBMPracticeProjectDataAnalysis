# IBM Data Analysis with Python - Practice Projects
This repository contains practice projects completed as part of the IBM Data Analysis with Python course. The course provides hands-on experience in data analysis, utilizing popular Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn to manipulate and visualize data.

## Overview
The IBM Data Analysis with Python course covers a wide range of topics and techniques for analyzing and visualizing data. In this repository, you will find projects where I applied the knowledge gained from the course to solve real-world data analysis challenges. These projects help in understanding how to:

- **Importing Data Sets**: Learn how to import data from multiple sources using Python libraries to begin the data exploration process.
- **Data Wrangling**: Master data cleaning and preprocessing tasks such as handling missing values, normalizing data, and converting categorical variables into numerical ones.
- **Exploratory Data Analysis (EDA)**: Perform statistical analysis using measures like mean, median, and mode, visualize data distributions, and apply methods like Pearson correlation and Chi-square tests to analyze relationships.
- **Model Development**: Develop linear regression models, evaluate their performance using metrics like R-squared and mean square error, and refine models using techniques such as polynomial regression and pipelines.
- **Model Evaluation and Refinement**: Evaluate and refine models using Ridge Regression, identify overfitting and underfitting, and optimize models with Grid Search for hyperparameter tuning.

For more details on the course, visit the [IBM Data Analysis with Python course](https://www.coursera.org/programs/sobma/learn/data-analysis-with-python?authProvider=bancolombia&source=search).

## Projects

### 1. Project 1: Insurance Cost Analysis
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
