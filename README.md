# Global Data Professional Salary Analysis

## Project Goal
This personal project aims to identify factors that influence data professional salaries & determine how those factors impact salaries based on the data in the Annual Global Data Professional Salary Survey in 2019.

## Data
The Annual Global Data Professional Salary Survey conducted in 2019 collected responses from 882 data professionals across 46 countries. The dataset contains various information such as salary, education, years of experience in data jobs, hours of work per week, and other related variables.

The dataset is available in this repository [here](data/original-data/2021-data-professional-salary-survey-responses.xlsx).

_Note: The data in the survey was self-reported and may contain biases or errors._

## Method
This analysis employs a combination of descriptive analysis, linear regression, and clustering techniques to gain insights into the factors influencing data professional salaries.

Descriptive analysis: The data is examined using descriptive statistics to identify factors such as weekly working hours, number of databases, primary database, job title, and education level that may impact salary levels.

Linear regression: A linear regression model is employed to analyze the impact of experience levels on salaries. By examining the relationship between years of experience and salary levels, this technique provides insights into the influence of experience on earning potential.

Clustering using Principal Component Analysis (PCA): Principal Component Analysis is applied to uncover underlying patterns and groupings within the dataset. By performing clustering analysis, five distinct clusters of data professionals are identified, shedding light on salary variations and other factors within each cluster.

## Result & Recommendations
The analysis reveals that years of experience with the primary database or in data jobs are not reliable indicators of salary levels. Other factors, such as weekly working hours and number of databases, as well as categorical factors like primary database, job title, and education level, may impact salary. Future analysis should consider these factors to comprehensively assess the various factors that may impact salary.

The Tableau storyboard can be found [here](https://public.tableau.com/app/profile/goghcore/viz/DataProfessionalSalaryAnalysis2019/DataProfessionalSalaryAnalysis).
