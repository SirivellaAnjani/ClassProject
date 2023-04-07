# Exploratory Data Analysis
###### Examined cars sold on the Quikr marketplace using pandas and matplotlib.  
<img src="https://user-images.githubusercontent.com/122895160/229857742-4e338f1f-4655-4b9c-ace0-80e1a1458bfe.png" width="200" height="100">

Exploratory Data Analysis (EDA) is an approach to analyzing and understanding data by summarizing its main characteristics, identifying patterns, and discovering relationships between variables. The primary goal of EDA is to gain insights and formulate hypotheses that can guide further analysis.

EDA is important because it enables data analysts to get an initial understanding of the data they are working with, without making assumptions or relying on preconceived notions. This can be particularly useful in situations where the data is complex, heterogeneous, or contains missing values.

The main steps are:

1. Data Cleaning and Preparation: This involves checking the data for errors, inconsistencies, and missing values. It may also involve transforming the data to make it more suitable for analysis.
1. Univariate Analysis: This involves analyzing individual variables to identify their distribution, central tendency, and variability. This may involve visualizing the data using histograms, box plots, or density plots.
1. Insights and Conclusions: This involves synthesizing the results of the previous steps to draw conclusions and generate insights. These insights may be used to guide further analysis or to develop hypotheses for future research.

Overall, EDA is a valuable tool for data analysts to gain insights and develop an understanding of the data they are working with. By identifying patterns, relationships, and outliers, EDA can help analysts to make more informed decisions and improve the accuracy of their analyses.

## Summary of Models
On creating the first model, the following observations were made:
- Coefficient is small and negative, meaning a weak negative correlation between Kms Driven and Price of car
- R2 value is negligible with a high Mean Square Error, indicating that the model does not fit the data well
- Initial Analysis suggests using another independent variable  

As a result of the previous model, another variable was chosen and examined:
- R2 value is higher by an order of 2, meaning the relationship between Price and Year is significantly stronger than Price and Kms driven.
- R2 value is still negligible with a high Mean Square Error, indicating that the model does not fit the data well
- Potential for further Analysis - explore different machine learning models on the dataset

## Reading
Followed the applicabile preprocess steps in [Towards Data Scicence post](https://towardsdatascience.com/exploratory-data-analysis-eda-a-practical-guide-and-template-for-structured-data-abfbf3ee3bd9).  
Explored data using the pandas functions, laid out in [Analytics Vidya blog post](https://www.analyticsvidhya.com/blog/2021/04/20-must-known-pandas-function-for-exploratory-data-analysis-eda/).
