# Amazon Vine Analysis (Big Data)
## Overview
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. This program provides products and then pays participants to write reviews for said projects. 

I selected the "toys" dataset for review. I took the following steps: Use PySpark to perform the ETL process to extract the dataset; transform the data; connect to an AWS RDS instance; and load the transformed data into pgAdmin. After that, I used Pandas to determine if there was any bias toward favorable reviews from Vine members in my dataset. 

## Results

![image](https://user-images.githubusercontent.com/102322707/184434051-6c520c4b-8893-4308-9ee9-6f691fbdb2a2.png)


![image](https://user-images.githubusercontent.com/102322707/184434072-9e6dc5b4-10b3-4b1f-96c2-5a67da471ce8.png)


- How many Vine (paid) reviews and non-Vine (unpaid) reviews were there?

  The total number of paid reviews is 1,266.
  
  The total number of unpaid reviews is 62,028.
  
  Only 2% of the reviews were from the Amazon Vine Program.  

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

  The total number of paid 5-star reviews is 432.
  
  The total number of unpaid 5-star reviews is 29,982.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

  The percentage of paid 5-star reviews is 34%.
  
  The percentage of unpaid 5-star reviews is 48%.
  
## Summary

I expected there to be bias towards 5-star reviews in the Amazon Vine Program (paid reviewers).  The results were surprising such that only 1/3 of paid reviewers gave 5-star reviews while almost 1/2 of unpaid reviewers did! So, it seems that there could be a bias of the paid participants towards not giving 5-star reviews in order to be perceived as providing a more fair review for their services.

I would recommend additional analysis in order to determine if there is any type of review bias occuring for Amazon Vine Program members. A direct survey of these participants to determine what factors influenced their review results would be beneficial.  

Another consideration would be the extremely small number of reviews contributed by the Amazon Vine Program members (only 2%) which would be too small to be considered a fair sample size for comparison.  The program could be evaluated as a whole, instead of coming to a conclusion based on one data set/category.

## Resources
Data: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Toys_v1_00.tsv.gz

Applications/Technology: AWS RDS; Google Colab; PostgreSQL; pgAdmin 4; and Jupyter Notebook


