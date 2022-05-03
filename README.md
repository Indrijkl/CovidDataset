# Ollist-Brazillian-Ecommerce (Meachine Learning-Unsupervised Portofolio)

This repository was made to store data about our final project. This project is part of the requirement in completing the Data Science study program at Purwadhika Startup & Coding School. This notebook contains EDA, seller segmentations and customer segmentations from the dataset Brazilian E-commerce Olist. The dataset used can be accessed freely from https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce.

# Table of Contents
●	Background

●	Problem Statement

●	Data Understanding

●	Modeling

●	Business Recommendation

●	File Content

●	Reference


# Background
In the era of technologies, E-commerce businesses are emerging everywhere. E-commerce is a business model which allows sellers and buyers to do transactions online through the internet. Through the ease of E-commerce platform, we can see the rise of customers each year. 

In the field of E-commerce, one of the business models that can be found is the marketplace. Marketplace is a business model that provides a platform for sellers and buyers to meet. The platform provides convenience for buyers to browse products and sellers to showcase products. One of the leading marketplace in Brazil is Olist.

![image](https://user-images.githubusercontent.com/99407430/166421057-70cdfae3-b8e6-4a35-808f-c22cc87705f5.png)

Revenue that is generated from this business model marketplace comes from paid features, paid commercials, payment gateway, and partnerships. Number of users and large traffic is important to increase the revenue of the marketplace. Few ways that can be done in order to increase user and traffic, is to start a Marketing Campaign that offers discounts to customers. Usually the company would put aside 5-12% from the total revenue to its campaign budget. The only problem that would arise from this matter is not reaching the desired goal from the campaign. A marketing campaign can be deemed successful when a certain number of new users signed up.

To increase the effectiveness of the campaign, one of the methods is to do Customer Segmentation and Seller Segmentation. Segmenting aids the marketplace to cluster customers and sellers together based on their similar traits. With segmentation, the marketplace will be able to formulate better strategies to increase users and transactions. Based on a recent survey done by Researchscape and Evergage in the year 2020, marketer agrees that personalisation leads to better connection with customers and from that strong impact can be attained.

# Business Problem Statement:
Business Problem Statement for Machine Learning

## How to segment customers so we can divide customers based on their shopping behavior?
  ●	Value: Customer Segmentation
  
  ●	Goals: Cluster customers based on their shopping behavior

## How to segment sellers so we can divide sellers based on their selling behavior?
  ●	Value: Seller Segmentation
  
  ●	Goals: Cluster seller based on their selling behavior

# Data Understanding
Based on the problem statement above, through data analysis our team will provide  solutions for the Brazilian E-commerce company Olist. The dataset provided has been gathered from the year 2016 until the year 2018. The data contains various information regarding customers, sellers and products. In our EDA, we only use columns associated with customers and sellers transactions, other columns were dropped. 

![image](https://user-images.githubusercontent.com/99407430/166421252-3f3a6777-bb6b-4a0c-a937-0baa9a820fdd.png)

# Modeling:
## RFM Segmentation:
In this section, our team generates Recency, Frequency, and Monetary scores for customers. The three variables could characterize the customer’s transaction behavior. RFM stands for:

●	Recency: How recent was the customer's last purchase? Customers who recently made a purchase will still have the product on their mind and are more likely to purchase or use the product again

●	Frequency: How often did this customer make a purchase in a given period? Customers who purchased once are often more likely to purchase again.

●	Monetary: How much money did the customer spend in a given period? Customers who spend a lot of money are more likely to spend money in the future and have a high value to a business.

From the RFM scores, we can cluster different customers together to its respective RFM segments.

## K-Means Clustering:
Our team uses the K-Means method to cluster the different sellers to its respective clusters.

# Business Recommendation:
![image](https://user-images.githubusercontent.com/99407430/166421673-3ea37556-07a9-40a3-94ba-22100b7695de.png)

# File Content:
●	Img: Folder of images used in this project

●	Tableu: Folder containing screenshot of Tableau Dashboard

●	Dataset:
    
  ○	Olist_customers_dataset.csv
  
  ○	Olist_dataset_merge.csv
  
  ○	Olist_geolocation_dataset.csv
  
  ○	Olist_order_items_dataset.csv
  
  ○	Olist_order_payments_dataset.csv
  
  ○	Olist_order_reviews_dataset.csv
  
  ○	Olist_orders_dataset.csv
  
  ○	Olist_products_dataset.csv
  
  ○	Olist_sellers_dataset.csv
  
  ○	Product_category_name_translatioon.csv

