# Amazon_Vine_Analysis

## Overview
In this project, we had access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. I picked the instrumental database and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next i used SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.

### How many Vine reviews and non-Vine reviews were there?

<img width="817" alt="first" src="https://user-images.githubusercontent.com/108194577/196841439-bd192a8b-d8d3-4ea9-a295-c6a821038aac.PNG">

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

<img width="574" alt="second" src="https://user-images.githubusercontent.com/108194577/196841465-90a5d491-beb2-46e5-967c-edcf83e95879.PNG">

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

<img width="488" alt="image 2" src="https://user-images.githubusercontent.com/108194577/196841229-f915041c-72f7-4fa5-915d-25dc806842a4.PNG">

## Summary
The results from the analysis indicate a positivity bias towards the Vine program. 
