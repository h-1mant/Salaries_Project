# Salary Estimation Portfolio

Exploration of Descriptive and Inferential Statistics (Python)

### Methods Used
- Data Analysis and Visualization
- Hypothesis Testing
- Confidence Intervals

### Libraries Used
- Python 3
- Numpy
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Jupyter

Description
---
The purpose of this project is to visualize Placement Statistics, for the Electronics and Communication Batch, 2019-23 at my University. The project explores the possibilty of gender bias in compensation, along with a detailed Sector-Wise split-up. Finally, the One-Sample T-test is used to test the **Null Hypothesis**: Average Overall Compensation = 11LPA, and derive the Confidence Intervals for the average package.

Data
---
The data used to predict the average CTC contains records of 96 students (anonymized) as of December 5, 2022.  
Attributes include
- Gender 
- CTC (_Cost to Compensation_)
- Sector

Summary
---
As per the study, the Telecom Industry offered maximum jobs, the Tech Industry offered maximum pay, while the Healthcare industry offered maximum average pay. Despite there being a 2:1 Male:Female sex ratio, female candidates outperformed males (as per mean and median projections). No notable gender-bias in compensation was found.
The Two-tailed One Sample T-test applied to predict the population mean yielded rejection of the **Null Hypothesis: Mean CTC = 11LPA** and a final 99% Confidence Interval of **9.02 to 11.14LPA**.
