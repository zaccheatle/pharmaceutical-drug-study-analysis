# Matplotlib Analysis Project

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

3 - Created line and scatter plots w/regression analysis to understand the relationship between mouse weight and tumor volume. 


## Observations and Insights

### Demographic Summary
- The bar graph shows that Capomulin has the largest mice count at 230, and Zoniferol has the smallest mice count at 182. After removing duplicates the total number of mice observed in the study was 249; 124 female mice and 125 male mice.

### Correlation Summary
- The correlation between mouse weight and average tumor volume is 0.84; a strong positive correlation, suggesting that when the mouse weight increases the average tumor volume also increases.

- The regression analysis explains how much a change in mouse weight will change the average tumor volume. The R-squared value is 0.70, which means there is a strong positive relationship between mouse weight and average tumor volume. As mouse weight increases by .95, tumor volume increases by 21.55. 

- Based on this analysis we can conlude that drug regimines Capomulin and Ramicane are most effective at reducing tumor volume. 
