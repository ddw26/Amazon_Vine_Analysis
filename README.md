# Amazon_Vine_Analysis

## Overview
My work with Jennifer on the SellBy project was a success, and because of that, I have been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. The purpose of my analysis is to inform the decisions of manufacturers and publishers with regard to the value of Amazon's paid review program. My analysis was done largely using Google colab notebook and Python. I was given access to approximately 50 datasets, each one containing reviews of a specific product, from clothing apparel to wireless products. I picked one of the datasets and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Lastly I used PySpark to determine if there is any bias toward favorable reviews from Vine members. Below are the results, summary, and analysis for Jennifer to submit to the SellBy stakeholders.

## Results:

How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

## Analysis & Summary:
