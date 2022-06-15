# Amazon Vine Analysis

## Overview
For this project, we were tasked with a larger project: analyzing Amazon reviews written by members of the Amazon Vine program, a service that allows manufacturers and publishers to receive reviews for their products. With access to about 50 datasets, review data on pet products was collected and PySpark was used to conduct the ETL process. The data was then connected to a database hosted by AWS. Once the process was complete an analysis was conducted to determine if there is any bias toward favorable reviews from Vine Members. 

## Results
![Resources/dataframes.png](https://github.com/c-ramos/Amazon_Vine_Analysis/blob/bc19d51b7592d0b3be50df4199d622dfa92421cc/Resources/dataframes.png)

**How many Vine reviews and non-Vine reviews were there?**
* For the pet products, there were 170 Vine reviews and 3,7840 non-Vine reviews. 

**How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**
* There were 65 5-star Vine reviews and 20,612 non-vine 5-star reviews.

**What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?** 
*  53.85% of the Vine reviews were 5 star, and 47.34% of the non-Vine reviews were 5 star.

## Summary
As show in the table above, there are only 48% of 5 star Vine reviews in the dataset versus 54% of 5 star non-Vine reviews which suggests that there is no clear bias. There is a disproportionate amount of data because 170 out of 37,840 reviews were from Vine users.

