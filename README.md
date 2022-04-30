# Consumer-Behavior-Analysis-on-E-Commerce-Platform
Submitted to Prof. Amit Ganatra under CSE 521: Big Data Analytics, Winter 2022, SEAS, Ahmedabad University

Problem Statement

In today’s world, shopping has largely become an errand that is run online. Hence, an enormous amount of data is generated on a daily basis on various e-commerce platforms. This data contains potential insights that can allow e-commerce businesses to implement strategies that will help them optimize their product placements, and eventually the revenue. This project intends to harness the power of Big Data Analytics in order to generate these insights.

Solution

The data collected from the eCommerce platform can be processed using the concepts of parallelization by Apache Spark. The DataPrep and MatPlotLib libraries are then used to generate visualizations of data. It is divided on the basis Event-Type to allow the e-commerce platform to gain insights such as:
What are the most popular products viewed/added to cart/purchased?
How likely is a viewed product added to the cart?
How likely is a product in the cart purchased. 
What products are frequently bought together?  
K-Means clustering can then be used to perform Market Segmentation for the platform. 

Dataset

The dataset contains consumer behavior data from November 2019 for a major e-commerce multi-category store. It is a large dataset (5GB) taken from Kaggle: https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store
Columns
event-time: timestamp of the collected datapoint
event-type: view/cart/remove from cart/purchase depending on the customer action
product_id: the product that is undergoing the event
category_id: id corresponding to the category of the product
category_code: code corresponding to the category of the product
brand: name of the brand 
price
user_id
session_id
Tools Used

PySpark
DataPrep
MatPlotLib
SparkML
Pandas
Kaggle Notebook

Data Pre-Processing

Missing Values: Rows carrying missing values were dropped.

Duplicate values: Rows with duplicate values were also dropped.


Data Analysis and Visualization

For Event-Type: View




For Event-type: Cart






For Event-type: Purchase









