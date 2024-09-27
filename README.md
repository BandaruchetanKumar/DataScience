# DataScience
## Introduction :

This report presents the results of an exploratory analysis conducted on a dataset containing information about movies. The primary goal is to understand key patterns, relationships, and factors influencing movie Success or failure.

## Data Collection and Cleaning :
- The Two different data sets are considered. One data set consists of 4803 rows and 4 columns and another data set consists of 4803 and 20 columns. There are some common columns in these two datasets. Further analysis required the second data set to determination of success and the failure of the movies. so i considered the second data set.
  
- Initial exploration revealed the missing values in columns such as Homepage, tagline,..
  
- The dupilicate values aren't identified.
  
## Data Exploration :
- Reviewed the first few rows of the dataset to understand its structure.
  
- Reviewed the required columns for the undestanding of data set. And Checked data types.

## Data Visualizations :
- Utilized histograms, box plots, and scatter plots to visualize the distribution of numerical variables.
- Created bar charts to explore the distribution of categorical variables such as 'original_language.'

## Outlier Analysis :
- Identified outliers in the 'revenue' variable using box plots and statistical methods.
  
- Considered the impact of outliers on subsequent analyses.
  
- The interquartile range technique is used for the revenue outliers handling.
## Feature Engineering :
- Calculated the return on investment (ROI) using the 'budget' and 'revenue' variables.
  
- Encoded categorical variables like 'original_language' using dummy variables.
## Correlation And Hypothesis Testing :
- Investigated correlations between 'budget' and 'revenue' using the Pearson correlation coefficient.
  
- Tested the hypothesis that there is a significant difference in average revenue between successful and unsuccessful movies.
  
## Patterns And trends :
- Discovered a positive correlation between 'budget' and 'revenue.'
  
- Identified genres that tend to have higher popularity and revenue.
  
## Recommendations for further analysis :
- Explore the impact of specific genres, release dates, and promotional strategies on movie success.
  
- Consider sentiment analysis on movie overviews to understand the emotional tone associated with successful movies.
## Limitations And Considerations :
- Limited by the availability of certain data, such as detailed marketing strategies or critical reviews.
  
- Results may be influenced by outliers, and their removal should be carefully considered.
## Conclusion :
- The analysis provided valuable insights into the relationships between various variables and potential factors contributing to movie success.
  
- Recommendations for further analysis can guide future investigations and decision-making processes.
