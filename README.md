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

There was a total of 94 paid reviews. 
<img width="679" alt="vine_paid_reviews" src="https://user-images.githubusercontent.com/65638310/163071756-b2618b6b-7002-4128-8239-0233f5e960b0.png">

There was a total number of 40471 non-Vine paid reviews.
<img width="696" alt="non-paid_reviews" src="https://user-images.githubusercontent.com/65638310/163071934-371ba46e-7c5c-453a-94c4-b0dfb8faa360.png">

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There was reviews that were 5 stars that were from Vine members. 

<img width="618" alt="5vine" src="https://user-images.githubusercontent.com/65638310/163072785-074ea717-f01e-470d-9e4c-e3c123d36c36.png">


There was reviews with 5 stars from non-Vine members.

<img width="687" alt="5nonvine" src="https://user-images.githubusercontent.com/65638310/163072916-2acd0401-7b73-425b-8ae1-42cce7c6b00b.png">


* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

The percentage of Vine member reviews that were 5 stars was 51.06%.
<img width="507" alt="Vine%5" src="https://user-images.githubusercontent.com/65638310/163073327-4d364439-6033-4893-91f8-efcec085b8f5.png">

The percentage of non-Vine members that were 5 stars was 38.70%.
<img width="517" alt="non5%" src="https://user-images.githubusercontent.com/65638310/163073424-4d4deae2-14ec-4884-a069-f928b47184fd.png">


<!--Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement. -->

## Summary
After extracting, transforming, and analyzing the data, it was determined that there was to some degree positive bias from paid members compared to non-paid members. More members of Vine who were paid to write reviews overall, gave more 5 star reviews than those who were not paid. 

An additional analysis that could have been done to the dataset to support is to look at the percentage of Vine reviews that have 1 star compared to those who are not Vine members and have 1 star. It would also be a great idea to see the average reviews from both Vine and non-Vine members.
