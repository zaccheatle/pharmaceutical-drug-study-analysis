# Pymaceuticals Drug Study Analysis

## Project Summary and Study Background
Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this project is to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens and provide a top level summary.

## Tools Used
Pythons Matplotlib and Pandas Libraries

## Summary of Analysis
1 - Cleaned and organized the dataset using pandas
provide summary statistics of the tumor volume for each drug regimen
calculate final tumor volume for the four most prominent drug regimens

2 - Created bar charts and pie charts in Matplotlib to visualize analysis of the following criteria;
total number of mice in study
gender breakdown of mice

3. Created a box and whisker plot to get the final tumor volume for each drug regimen to compare effectiveness. 

4. - Created line and scatter plots w/regression analysis to understand the relationship between mouse weight and tumor volume. 


## Observations and Insights

### Demographic Summary
- Capomulin has the largest mice count at 230, and Zoniferol has the smallest mice count at 182. After removing duplicates the total number of mice observed in the study was 249; 124 female mice and 125 male mice.

### Regression Analysis for Capomulin Treatment
- The correlation between mouse weight and average tumor volume is 0.84; a strong positive correlation. When mouse weight increases the average tumor volume also increases.

- The regression analysis explains how much of the variability in average tumor volume is influence by the variability in mouse weight. With an R-squared value of .70 there is a positive linear relationship between mouse weight and average tumor volume; a one gram increase in mouse weight results in .95 mm3 increase in tumor volume. 

- Based on this analysis we can conlude that drugs Capomulin and Ramicane are most effective in reducing tumor volume, and mice treated with Ramicane had the lowest average final tumor volume compared to the other drug regimens. 
