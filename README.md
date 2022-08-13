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

There are 44 vine reviews rated 5 stars.


<img width="981" alt="Vine Reviews (5 Stars)" src="https://user-images.githubusercontent.com/104735724/184512201-eaa42880-cffa-40b9-9511-2bb653939139.png">



There are 14,626 non-vine reviews rated stars. 


<img width="675" alt="Non Vine reviews (5 stars)" src="https://user-images.githubusercontent.com/104735724/184512562-6d0db5c0-09c0-4fc9-a06f-1305fb4a2500.png">



3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?


