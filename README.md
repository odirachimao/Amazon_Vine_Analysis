# Amazon_Vine_Analysis

## ANALYSIS OVERVIEW:

This project analyzes the Amazon Vine program to better understand if there is a bias towards 5 star ratings for those that were paid vs. unpaid. We have access to approximately 50 datasets, with each one containing reviews of a specific product, ranging from clothing apparel to wireless products. In this project, our main focus will be on Video Game reviews. The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.


## RESULTS:

1. How many Vine reviews and non-vine reviews were there? 

There are 90 Vine Reviews.


<img width="494" alt="No of Vine Reviews" src="https://user-images.githubusercontent.com/104735724/184511963-fb8016e6-5d10-4761-bf33-cd7a945d7903.png">



There are 37,385 Non-Vine Reviews.


<img width="494" alt="No of Non-Vine Reviews " src="https://user-images.githubusercontent.com/104735724/184511980-0d4e4301-da61-458e-9f09-2ecd7638967c.png">


2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars? 

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

There are 44 vine reviews rated 5 stars or 49% of the total. 


<img width="981" alt="Vine Reviews (5 Stars)" src="https://user-images.githubusercontent.com/104735724/184512201-eaa42880-cffa-40b9-9511-2bb653939139.png">



There are 14,626 non-vine reviews rated stars or 39% of the total. 


<img width="983" alt="Non Vine reviews (5 stars)" src="https://user-images.githubusercontent.com/104735724/184513289-1ab0cc0b-77bc-4c4e-be15-237104ad6b7f.png">


## RESULT SUMMARY: 

From our results, there is some bias for reviews in the Vine program as 49% were rated 5 stars vs. 39% of non-Vine reviews. However, with the sample size of 90 total vine reviews, the sample size is very small to conclude that. An additional analysis could also be to do a Paired t-test to compare Vine reviews and Non-Vine reviews to understand if there is a statistical difference between the two groups.


