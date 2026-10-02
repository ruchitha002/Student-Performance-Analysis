# Project 02 — Student Performance Analysis

## Pluto Academy Data Analytics Internship

### Domain
Data Analytics

## Project Overview

This project analyzes student academic performance using the StudentsPerformance dataset.

The analysis examines student scores across mathematics, reading, and writing and investigates how performance varies according to parental education, test preparation, and gender.

## Dataset

The dataset contains 1,000 student records and 8 original columns.

The original variables include:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

The project includes:

1. Dataset inspection
2. Missing-value analysis
3. Duplicate-value analysis
4. Descriptive statistics
5. Analysis by parental education
6. Test preparation analysis
7. Correlation analysis
8. Gender-based performance comparison
9. Total score distribution
10. At-risk student segmentation
11. Group-level at-risk analysis
12. Principal's Report

## Key Questions

- How does parental education level relate to student performance?
- Does completing the test preparation course improve average scores?
- Is there a strong relationship between reading and writing scores?
- Do male and female students perform differently across subjects?
- How are total scores distributed?

## At-Risk Definition

A student is classified as at-risk if they score below 50 in at least one of the following subjects:

- Math
- Reading
- Writing

## Visualizations

The project includes:

- Box plot
- Bar charts
- Correlation heatmap
- Grouped bar chart
- Histogram
- Scatter plot

## Project Structure

```text
Project_02_Student_Performance_Analysis/
│
├── data/
│   ├── StudentsPerformance.csv
│   └── README.md
│
├── notebooks/
│   └── project_02_student_performance_analysis.ipynb
│
├── outputs/
│   └── analysis visualizations
│
├── .gitignore
├── README.md
└── requirements.txt
Conclusion

The analysis identifies patterns in student performance across academic subjects and different student groups. The results can be used to identify students who may require additional academic support and to guide targeted educational interventions.