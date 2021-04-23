# Amazon_Vine_Analysis

## Overview
The purpose of this analysis was to determine if there is a higher percentage of 5 Star Ratings for paid(Vine) versus unpaid reviews for video games on Amazon. 

## Results
After cleaning the data, a paid and unpaid DataFrame was created. The first 20 rows of each are shown in the images below:

![Paid Dataframe](https://raw.githubusercontent.com/jdwrhodes/Amazon_Vine_Analysis/main/resources/paid_df.png 'Paid DataFrame')

Paid DataFrame

![Unpaid DataFrame](https://raw.githubusercontent.com/jdwrhodes/Amazon_Vine_Analysis/main/resources/unpaid_df.png 'Unpaid DataFrame')

Unpaid DataFrame

A count of each DataFrame yielded 90 paid(Vine) reviews and 37,831 unpaid reviews. This is show below:
![Paid and Unpaid Review Count](https://raw.githubusercontent.com/jdwrhodes/Amazon_Vine_Analysis/main/resources/paid_unpaid_reviews.png 'Paid and Unpaid Review Count')

The number of 5 Star reviews was calculated for each, 44 5 Star paid reviews and 14704 5 Star unpaid reviews.
![Five Star Reviews](https://raw.githubusercontent.com/jdwrhodes/Amazon_Vine_Analysis/main/resources/each_review_count.png 'Five Star Reviews')

And the percentage of 5 Star reviews was 48.89% for paid and 38.87% for unpaid.
![Five Star Review Percentage](https://raw.githubusercontent.com/jdwrhodes/Amazon_Vine_Analysis/main/resources/percent_reviews.png 'Five Star Review Percentage')

## Summary
A few conslusions could be drawn from this dataset. One is that there does appear to be a bias for positive for paid reviews, at 10% higher for paid vs unpaid. Something to keep in mind is that there is only 90 paid reviews, compared to over 37,000 unpaid. Meaning that there is 420 unpaid reviews for each paid review. Acquiring a larger paid sample set may be desirable. 

An additional analysis that could help mitigate this numerical difference would be to study another category of reviews other than video games, like electornics. That would keep it in the same realm of product. By assessing any bias in another dataset could bolster the results of this dataset.
