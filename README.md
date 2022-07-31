# Amazon Vine Analysis
## Overview
### Purpose
The Amazon Vine program allows companies to give their product to Amazon Vine members in exchange for a review of the product. The purpose of this analysis is to determine if paid Vine program Amazon reviewers are biased to be more favorable than unpaid reviewers. We will be investigating a dataset of Amazon book reviews. 

## Results
- The number of Vine reviews in our dataset was 0, compared to 378,638 non-Vine reviews. The lack of Vine reviews in this dataset means that we will be unable to determine bias in the reviews.
- The number of 5 star Vine reviews in our dataset was 0, compared to 227,734 5 star non_Vine reviews.
- We cannot determing a percentage of 5 star Vine reviews since the number of total Vine reviews is 0. The percentage of 5 star non-Vine reviews is 60.15%.

Vine Reviews             |  Non-Vine Reviews
:-------------------------:|:-------------------------:
![image](https://user-images.githubusercontent.com/102445183/182042144-79574e58-1eeb-4e8f-8cfc-21394fbaa411.png)  |  ![image](https://user-images.githubusercontent.com/102445183/182042181-e27a2c01-be96-447d-9c04-cf4649d4cab5.png)


## Summary
There is not enough information to determine whether or not there is bias between paid and unpaid reviews. In our book reviews dataset, there were no reviews that satisfied all three requirements: over 20 total votes, majority helpful votes, and part of the vine program.
### Recommendations
Additional analysis needs to be completed on a dataset that includes paid Vine reviews to determine if there is bias. We can investigate Amazon's other two datasets with book reviews to determine if either contain Vine reviews, or we can select a different product category for our analysis. Alternatively, we can relax the requirements on this dataset, including reviews with less votes or less helpful votes.   

Another analysis to determine bias would be to investigate if the percentage of 4 OR 5 star ratings differed between Vine and non-Vine reviews. Similarly, we could analyze the percentage of 1 star ratings.   

If there is bias toward favorable reviews, we would see a significantly higher percentage of 5 star reviews in the Vine reviews dataframe than in the non-Vine reviews dataframe. If there is no bias we would see very similar percentages of 5 star reviews between the Vine and non-Vine reviews, or the Vine reviews would have a lower percentage of 5 star reviews.
