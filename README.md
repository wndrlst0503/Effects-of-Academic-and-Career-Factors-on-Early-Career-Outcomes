## Overview
This project analyzes how academic background and internship experience relate to early-career outcomes. Using the “Education & Career Success” dataset from Kaggle, we explored how factors such as field of study, internships completed, and job offers are associated with outcomes like starting salary and career satisfaction.

The dataset contains 400 records and 19 variables related to students’ academic performance, extracurricular activities, and early career results. For this analysis, we focused on four key variables: field of study, internships completed, job offers, and starting salary.

Dataset: https://www.kaggle.com/datasets/adilshamim8/education-and-career-success

## Research Questions
1. Is there an association between the number of internships completed and the number of job offers received?
2. Is the proportion of graduates with high career satisfaction different between STEM and non-STEM fields?
3. Which log-linear model best explains the relationships among field of study, internships, and job offers?

## Methods
We applied statistical methods for categorical data analysis using R:

- Chi-square test of independence  
- Two-proportion z-test  
- Log-linear modeling

These methods were used to examine associations between internships, field of study, job offers, and career satisfaction.

## Key Findings
The analysis showed a strong association between the number of internships completed and the likelihood of receiving job offers. The results suggest that internship experience plays an important role in early-career opportunities and job market outcomes.

## Files
- `early_career_outcomes_data.csv` – dataset used for analysis  
- `final_report.pdf` – full project report  
- `project_presentation.pdf` – project presentation slides
