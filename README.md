# Amazon_Vine_Analysis

##  Overview of Project
In this project I picked an Amazon Vine program dataset and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset. 

## Results
- How many Vine reviews and non-Vine reviews were there?
  - 261 Vine, 24040 non-Vine reviews. 

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - 106, 5-star Vine, 10899 5-star non-Vine reviews. 

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - 41% 5-star Vine, 45% 5-star non-Vine reviews. 

## Summary
It does not seem that there is any correlation between Vine vs non-Vine reviews for products in this category receiving 5-stars (41 vs 45% of both are 5-stars). Next I would do further analysis on the other star ratings to support my hypothesis. 
