# Amazon Vine Analysis (Big Data)
## Overview
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. This program provides products and then pays participants to write reviews for said projects. 

I selected the "toys" dataset for review. I took the following steps: Use PySpark to perform the ETL process to extract the dataset; transform the data; connect to an AWS RDS instance; and load the transformed data into pgAdmin. After that, I used Pandas to determine if there was any bias toward favorable reviews from Vine members in my dataset. 

## Results

![image](https://user-images.githubusercontent.com/102322707/184434051-6c520c4b-8893-4308-9ee9-6f691fbdb2a2.png)


![image](https://user-images.githubusercontent.com/102322707/184434072-9e6dc5b4-10b3-4b1f-96c2-5a67da471ce8.png)


- How many Vine reviews and non-Vine reviews were there?

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?


## Summary

The summary states whether or not there is bias, and the results support this statement

An additional analysis is recommended to support the statement

## Resources
File: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Toys_v1_00.tsv.gz


