# Amazon_Vine_Analysis

<!-- Overview of the analysis: Explain the purpose of this analysis. 
 analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. determine if there is any bias toward favorable reviews from Vine members in your dataset. -->
## Overview
The purpose of this assignment was to analyze data from Amazon reviews from members who are part of a paid program: Vine Analysis. The data was extracted, transformed, connectted to AWS RDS instance, and laoded into pgAdmin. Then it was determined if there is any bias towards Vine members or unpaid reviews. 
 
<!--Results: Using bulleted lists and images of DataFrames as support, address the following questions:
How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?-->
## Results 

* How many Vine reviews and non-Vine reviews were there?

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

<!--Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement. -->

## Summary
After extracting, transforming, and analyzing the data, it was determined that there was to some degree positive bias from paid members compared to non-paid members. 

An additional analysis that could have been done to the dataset to support is to look at the percentage of Vine reviews that have 1 star compared to those who are not Vine members and have 1 star. 
