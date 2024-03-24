# **Zillow Time Series Modeling: Forecasting Future Real Estate Prices within Kansas City**

<img src="images/miamicover.png" width="750">

## Project Contributors: 
** Gideon Biwott,Silah Rugut,James Nyamu,Caroline Kisaulu,Eunita Nyage,Lorrah Ngine**


## Table of Contents
* [Overview](#overview)
* [Business Understanding](#business-understanding)
* [Data Understanding and Preparation](#data-understanding-and-preparation)
* [Model Training and Testing](#model-training-and-testing)
* [Recommendations and Conclusion](#Recommendations-and-Conclusion)

## Resources
-Zillow Research datasets
-Economic indicators and demographic data
-Python libraries for data analysis and modeling (e.g., pandas, scikit-learn, statsmodels)
-Jupyter Notebook for code development and documentation
-Visualization tools like Matplotlib and Seaborn for data visualization
-Machine learning frameworks for model training and evaluation.

## Overview
The objective of this project is to forecast real estate prices in Time Series Analysis for various zip codes in Kansas City using historical data from Zillow Research. As a consultant for  Wisconsin realtors investment firm, the goal is to provide accurate predictions to guide investment decisions and maximize returns.

By leveraging advanced time series forecasting techniques and comprehensive data analysis, this project aims to provide valuable insights and actionable recommendations to support informed real estate investment decisions in Kansas City for the Wisconsin real estate investment firm.

## Business Understanding
Wisconsin realtors is an investment firm in Kansas city in the US that has contracted us as consultants to help them make the best real estate investment decisions.

Our task is to identify the best 5 Zip Codes which we believe will have the highest ROI after 3 years of purchase. i.e. We want the zipcodes that we believe will appreciate the most in value after 3 years. These predictions will be made using Time Series modeling. 


## Data Understanding and Preparation

The data provided to us consists of information pertaining to over 14,000 Zip codes within the United States. The data is located within the ‘data/zillow_data.csv’ file in this repository. In total, there are 14,723 rows of data and 272 columns. Of these 272 columns, 7 of the columns are described below. The remaining 265 columns are records of the given Zip code’s average home value between April, 1996 and April, 2018. The other 7 columns are:


* ‘RegionID’- Each record contained a unique ID number. This column deemed unimportant for our analysis.
*’RegionName’-This is the column that provides the Zip code for the given row.
*’City’- The name of the city in which the Zip code is located.
*’State’- The name of the State in which the City is located.
*’Metro’-The name of the Metro region.
*’CountyName’-The name of the County
*’SizeRank’- The ranking of the particular Zip code’s size relative to other records in the dataset.


Our project goal is to identify the best top 5 zipcodes within Kansas city for our client to invest in for maximum projected returns.


<img src="images/miamicover.png" width="750">


Having looked at the number of cities within the County region and understanding how each city is divided into Zip codes, we identified the top 5 zipcodes with the highest ROI that our client can invest in.




## Modelling
Having filtered our dataset to only include Zip codes with the highest ROI, we model each zip code separately to forecast the projected prices after 3 years.

In our project, we use ARIMA model with p,d,q combination with the least MSE.


## Findings
Our top 5 zipcodes in returns were Zipcode : 64106,66106, 64114, 64112,66103 in Kansas city.
Zipcode 64106 had the highest return on investment.


## Recommendations 

Invest in Growth Areas: Focus on regions showing strong, consistent property value increases, such as Zip Code 66103. These areas demonstrate robust market conditions and potential for high return on investment (ROI).

Diversify Investments: Consider diversifying investments across multiple zip codes, including 66106 and 64112, to spread risk and capitalize on different market dynamics.

Monitor Market Trends: Keep an eye on long-term market trends, particularly the recovery and growth periods post-2012, to make informed investment decisions.

Consider Timing: Given the historical impact of economic downturns like in 2008, investors should be cautious about market timing and consider the broader economic indicators.



## Conclusion

The Kansas City real estate market has experienced a significant recovery since the 2008 financial crisis, with a consistent upward trend in property values, especially post-2012.

The market shows a range of investment opportunities, from more affordable properties in areas like Zip Codes 66106 and 66103 to higher-end markets in areas like Zip Code 64112.

The analysis suggests a robust market with potential for growth, especially in certain zip codes identified as having strong upward price trends.

Investment strategies should be informed by historical market performance, current market conditions, and future market forecasts, considering the long-term upward trend in property prices and regional variances.