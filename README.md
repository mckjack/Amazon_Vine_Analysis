# Amazon_Vine_Analysis
## Overview
This challenge focused mainly on the Amazon Vine Program. Our end goal was to determine if there is a bias toward favourable reviews from Vine members. We decided to focus our data on the US Reviews of music. Through this analysis we used tool such as PySpark to perform ETL Processes on the dataset we worked with. We extracted the data, transformed the data, and then connected the data to an AWS RSD instance. From there we loaded the data intp pgAdmin to calcute certain metrics. 
## Results
Below, is an image that shows the following metrics, total number of vine and non-vine reviews, total number of vine and non-vine 5 star reviews, and the percentage of 5 star reviews from vine and non-vine members.

![Image](https://github.com/mckjack/Amazon_Vine_Analysis/blob/main/Images/Reviews.png)

We see the total for the following 
- Total Vine Reviews = 7
- Total Non-Vine Reviews = 105,979
- Total 5-Star Vine Reviews = 0
- Total 5-Star Non-Vine Reviews = 67,580
- Total Percentage of 5 Star Vine Reviews = 0.0 %
- Total Percentage of 5 Star Non-Vine Reviews = 63.77 %

## Summary 
We summarize that the results from this data show no bias toward favourable reviews from Vine members since there was only 7 total Vine Reviews. We see that when reviewing music the Non-Vine members were 63.77 % likely to post a 5-star review where as there was 0 5-star reviews from Vine members. Additional insight could be provided by looking at the summary statistics of this dataset such as the mean, median, and mode of the reviews and also the standard deviation of the dataset. With this insight we can come to a better conclusion for why non-vine members are more likely to give reviews on music. 
