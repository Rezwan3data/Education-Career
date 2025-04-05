# Education & Career Sucess Correlation

**Date:** March 22, 2025

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
- [Findings and Discussions](#findings-and-discussions)
  - [Data Set 1](#data-set-1)
  - [Data Set 2](#data-set-2)
  - [Data Set 3](#data-set-3)
  - [Research Paper](#research-paper)
  - [Data Set 4](#data-set-4)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction

In this project, we run an analysis on 4 different datasets to understand how factors such as university rankings, GPA, field of study, geographic region, internships, and networking skills affect salaries and career progression in the US job market. Using multiple datasets, we aim to uncover trends that influence job promotions and overall work-life balance. Additionally, we incorporate a salary dataset from the UK, enabling us to compare salaries across different industries in both regions. 

Through interactive and insightful visualizations using tools such as Tableau and Python, this project will provide a data-driven perspective on how education, experience, and networking impact career success.

### Hypothesis Statement
Graduates from highly ranked institutions typically start off with higher starting salaries. However, this benefit is not just influenced by university ranking alone, but also by factors such as geographic location, field of study, internships, job satisfaction, certifications, and networking.

## Methodology

### Data Cleaning and Preparation
Before diving into the analysis, the datasets were carefully checked for any missing or inconsistent values. Any gaps in the data were either filled using appropriate imputation methods or removed if necessary to maintain data integrity. Categorical variables were converted into numerical formats using techniques like one-hot and label encoding, making them easier to analyze and interpret.

### Visualization Techniques
Various visualization tools such as Python (Matplotlib, Seaborn) and Tableau were used. A mix of scatter plots, bar charts, line graphs, box plots, and heatmaps helped illustrate key trends and relationships between important variables.

### Analytical Approach and Insights
The goal of this analysis was to understand what factors contribute to better job opportunities and higher salaries. By applying statistical analysis and exploring trends in the data, key insights were uncovered, offering valuable guidance for students and professionals looking to maximize their job prospects and earning potential.

## Findings and Discussions

### Data Set 1: Education & Career Success (Kaggle)
The analysis of the first dataset produced multiple visualizations. The university rankings were divided into four bins or Tiers:
- Tier 1: 0-50 ranking
- Tier 2: 51-200
- Tier 3: 201-500
- Tier 4: 500+

The analysis of the starting salary showed no visible difference across different university tiers.

The analysis of the starting salary showed no visible difference across different university tiers.

![Starting Salary across different University Tiers](path/to/image1.png)

### Data Set 2: Pay Scale Website
A second dataset from PayScale was utilized. The correlation between university rank and early career pay showed a different trend compared to Dataset 1.

![University Rank vs Early Career Pay](path/to/image2.png)

### Data Set 3: UK Data
This dataset examined whether geographic region affects salary by comparing various job sectors in the UK. 

![Mean Salary by Job Category](path/to/image3.png)

### Research Paper
The paper by Hans-Georg Wolff and Klaus Moser titled “Effects of Networking on Career Success: A Longitudinal Study” was critical in exploring the role of networking on career satisfaction and salary.

### Data Set 4: Alumni Connections and Networking
This dataset focused on alumni connections and their impact on employment rates. A regression analysis revealed that top universities tend to provide better alumni connections, which helps students secure high-paying jobs.

![World Rank vs Number of Employment Through Alumni](path/to/image4.png)

## Conclusion

This analysis shows that university rankings play a significant role in career success, especially concerning salary and job opportunities. However, networking also plays a crucial role in career progression, with top-ranked universities providing better networking opportunities through their alumni.

## References
1. [Fidelity: Average Salary in US](https://www.fidelity.com/learning-center/smart-money/average-salary-in-us)
2. [ZipRecruiter: Highest Paying Artist Jobs](https://www.ziprecruiter.com/g/Highest-Paying-Artist-Jobs)
3. [BLS: Secretaries and Administrative Assistants](https://www.bls.gov/ooh/office-and-administrative-support/secretaries-and-administrative-assistants.htm)
4. [Payscale: College Salary Report](https://www.payscale.com/college-salary-report/bachelors)
5. [ResearchGate: Effects of Networking on Career Success](https://www.researchgate.net/publication/23971043_Effects_of_Networking_on_Career_Success_A_Longitudinal_Study)
