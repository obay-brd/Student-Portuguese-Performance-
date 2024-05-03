# Student Performance Analysis in Python

This project focuses on analyzing the performance of students in Portuguese language courses based on various socio-economic and academic factors. The analysis is conducted using Python in a Jupyter Notebook environment, utilizing powerful data manipulation and visualization libraries.

## Project Description

The aim of this project is to identify patterns and correlations that affect student performance. By analyzing these factors, educational institutions can develop targeted interventions to improve student outcomes.

### Objectives
- To explore the relationship between student grades and various independent variables like family background, study time, failures, and school support.
- To apply statistical analysis to understand the impact of these factors on student performance.
- To visualize data distributions and correlations using plots and charts.

## Environment Setup

### Prerequisites
Ensure that Python 3.x and Jupyter Notebook are installed on your system. You can install them via Anaconda, which provides both in a single package.

### Dependencies
The project uses several Python libraries for data handling and visualization. Install the required libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn scipy
```

## Data
The dataset used in this analysis is titled student-por.csv, which includes records of students' academic and personal lives. This dataset is part of a publicly available collection from the UCI Machine Learning Repository.

## Data Attributes
- school - student's school (binary: "GP" or "MS")
- sex - student's sex (binary: "F" - female or "M" - male)
- age - student's age (numeric)
- address - student's home address type (binary: "U" - urban or "R" - rural)
- famsize - family size (binary: "LE3" - less or equal to 3 or "GT3" - greater than 3)
- Pstatus - parent's cohabitation status (binary: "T" - living together or "A" - apart)
- Medu - mother's education (numeric: 0 - none, 1 - primary education, ..., 4 - higher education)
- Fedu - father's education (numeric)
- traveltime - home to school travel time (numeric: 1 - <15 min., ..., 4 - >1 hour)
- studytime - weekly study time (numeric: 1 - <2 hours, ..., 4 - >10 hours)
- failures - number of past class failures (numeric: n if 1<=n<3, else 4)
- schoolsup - extra educational support (binary: yes or no)
- famsup - family educational support (binary: yes or no)
- paid - extra paid classes (binary: yes or no)
- activities - extra-curricular activities (binary: yes or no)
- nursery - attended nursery school (binary: yes or no)
- higher - wants to take higher education (binary: yes or no)
- internet - Internet access at home (binary: yes or no)
- romantic - with a romantic relationship (binary: yes or no)
- G1, G2, G3 - grades (numeric: from 0 to 20)


# Analysis

## Notebooks
The analysis is segmented into various sections, each in a Jupyter Notebook:

1. Data Cleaning - Preparing data for analysis by handling missing values and outliers.
2. Exploratory Data Analysis (EDA) - Conducting initial investigations on data to discover patterns, spot anomalies, and test hypothesis using summary statistics and graphical representations.
3. Statistical Analysis - Applying statistical tests to deduce the relationships between student performance and other variables.
4. Predictive Modeling - Building a regression model to predict final grades based on the identified significant predictors.


## Visualization
Data visualization is performed using matplotlib and seabean. These visualizations include:

- Scatter plots to identify relationships between continuous variables.
- Box plots to compare distributions across different categories.
- Heatmaps to show correlations between variables.


## Conclusions
Findings from this analysis provide insights into the factors that significantly impact student performance and suggest actionable steps for stakeholders in the educational sector.

Contact
For any inquiries or further discussions regarding the project, feel free to contact me at [obay.baradie32@gmail.com].
