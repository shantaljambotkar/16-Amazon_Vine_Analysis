# 16-Amazon_Vine_Analysis

## Overview
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. Using one of the 50 datasets provided and using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.

## Results: 

### Vine reviews paid

![Vine reivews Paid](Images/Vine_Reviews.png)

### Vine reviews unpaid

![Vine reivews Paid](Images/Vine_Reviews_N.png)

### Vine 5 Stars reviews paid 

![Paid 5 Star Reviews](Images/Vine_reviews_5Y.png)

### Vine 5 Stars reviews paid

![Unpaid 5 Star Reviews](Images/Vine_reviews_5N.png)

### Percentage of Vine reviews that were 5 stars and non-Vine reviews that were 5 stars

Percentage of paid 5 star reviews : 33.549467 % 

Percentage of unpaid 5 star reviews : 50.782954 %

## Summary: 
## In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. 

![Unpaid 5 Star Reviews](Images/Results.png)

## Then, provide one additional analysis that you could do with the dataset to support your statement.