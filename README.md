# Amazon_Vine_Analysis. 

## Overview of the analysis: 

Since my collaboration with Jennifer on the SellBy project was so successful, I've been given another, larger assignment: evaluating Amazon reviews published by Amazon Vine members. Manufacturers and publishers may get reviews for their products through the Amazon Vine programme. Companies such as SellBy pay a modest fee to Amazon and then supply things to Amazon Vine members who must then leave a review. 

I'll have access to about 50 datasets for this project.Each one features product reviews ranging from clothes to wireless devices. I'll have to choose one of these datasets and use PySpark to extract, convert, connect to an AWS RDS instance, and load the changed data into pgAdmin. Next, I'll utilise PySpark, Pandas, or SQL to see if there's any bias in your dataset toward positive Vine ratings. Then, for Jennifer to send to the SellBy stakeholders, I'll produce a summary of the findings. 

## Results: 

###### 1. How many Vine reviews and non-Vine reviews were there?

There were 39,976 reviews overall, including Vine and non-Vine reviews.


There were 107 Vine (paid) reviews in all.


There were 39,869 non-Vine (unpaid) reviews in total. 


<img width="362" alt="image" src="https://user-images.githubusercontent.com/93067732/155869577-5ed435a4-03ca-4724-82fe-c4d6303f906e.png">

<img width="325" alt="image" src="https://user-images.githubusercontent.com/93067732/155869588-d8e90570-0fed-4b89-9e12-15a52e54de08.png">

###### 2. How many Vine reviews were 5 stars?

There were 21,061, 5 star reviews in total, including Vine and non-Vine 5 star ratings.


There were 56 Vine (paid) 5 star reviews in total.


A total of 21,061 non-Vine (unpaid) 5 star reviews were submitted. 

<img width="442" alt="image" src="https://user-images.githubusercontent.com/93067732/155869688-6dc0d728-46ce-4468-bfa1-eb0f4bc0bf5d.png">

<img width="488" alt="image" src="https://user-images.githubusercontent.com/93067732/155869728-6f0149a6-74d7-480f-8c98-eff4d4f7a76a.png">


###### 3. What percentage of Vine reviews were 5 stars?. What percentage of non-Vine reviews were 5 stars?

The proportion of Vine (paid) participants who received 5 star evaluations was 52.3364 percent.


The proportion of non-Vine (unpaid) participants who gave 5 stars was 52.6850 percent. 

<img width="438" alt="image" src="https://user-images.githubusercontent.com/93067732/155869799-19c6ccfe-ceed-45b1-9e4a-f51e02e7a745.png">

<img width="500" alt="image" src="https://user-images.githubusercontent.com/93067732/155869822-ad7fd912-7aee-464d-816e-dc761fd4a8a0.png">

## Summary: 

We may conclude from the findings that there does not appear to be any positivity bias in terms of paid Vine participants creating more favourable product ratings than non-Vine (unpaid) individuals.

Both paid and unpaid reviewers gave the items a comparable rating of 5 stars; in fact, unpaid reviewers (52.68 percent) gave the products a little higher rating of 5 stars than Vine members (52.33 percent). 

We can conclude that there is no statistical positivity bias for Vine participants when it comes to providing 5 star reviews for Outdoor products, excluding statistical testing that could be done to determine if the sample sizes were large enough based on overall Vine participation, because there is a similar percentage of paid and unpaid reviewers who gave the products a 5 star review. 
