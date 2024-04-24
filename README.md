# Statistical Analysis of COVID-19 in Mexico

## Project Overview
This project conducts a thorough analysis of COVID-19 data provided by the Mexican government, accessible through Kaggle under a CC0 Public Domain License. It includes over 1 million anonymized patient records with 21 features covering pre-existing conditions and other demographic details.

## Key Objectives
- Predict Pandemic Outcomes: Utilize statistical analysis to enhance prediction capabilities for outcomes of pandemics like COVID-19.
- Understand Complex Effects: Explore how age, lifestyle habits, and comorbidities influence pandemic outcomes.

## Methodology
- Data Preparation: Standardized data using binary representations and handled missing values appropriately.
- Exploratory Data Analysis (EDA): Performed initial data analysis to understand the distribution and impact of various factors on patient outcomes.
- Statistical Testing: Conducted two main types of statistical tests:
  - Hypothesis Tests: Analyzed differences in COVID-19 mortality rates between age groups using proportion tests and bootstrap methods to estimate confidence intervals.
  - Chi-Squared Tests of Independence: Evaluated the association between comorbidities and COVID-19 outcomes, utilizing multiple datasets to ensure robustness of the results.

## Results
- Significant Differences in Mortality: Older adults (60+) show significantly higher mortality rates compared to younger individuals (18 and under).
- Impact of Comorbidities: A strong link was found between the number of pre-existing conditions a patient has and their likelihood of a severe outcome from COVID-19.

## Tools Used
- R: Utilized for statistical analysis and data visualization.
- Prop.test and Bootstrap: Methods for hypothesis testing and confidence interval estimation.
- Chi-Square Test: Used for testing the independence of categorical variables.

## Conclusion
The analysis confirmed significant demographic and health-related factors affecting COVID-19 outcomes. These insights can guide public health strategies and resource allocation in managing current and future pandemics.
