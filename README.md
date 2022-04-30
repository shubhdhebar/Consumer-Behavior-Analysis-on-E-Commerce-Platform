Readme

<https://github.com/shubhdhebar/Consumer-Behavior-Analysis-on-E-Commerce-Platform> 

**Problem Statement**

In today’s world, shopping has largely become an errand that is run online. Hence, an enormous amount of data is generated on a daily basis on various e-commerce platforms. This data contains potential insights that can allow e-commerce businesses to implement strategies that will help them optimize their product placements, and eventually the revenue. This project intends to harness the power of Big Data Analytics in order to generate these insights.

**Solution**

The data collected from the eCommerce platform can be processed using the concepts of parallelization by Apache Spark. The DataPrep and MatPlotLib libraries are then used to generate visualizations of data. It is divided on the basis Event-Type to allow the e-commerce platform to gain insights such as:

1. What are the most popular products viewed/added to cart/purchased?
1. How likely is a viewed product added to the cart?
1. How likely is a product in the cart purchased? 
1. What products are frequently bought together?  

K-Means clustering can then be used to perform Market Segmentation for the platform. 

**Dataset**

The dataset contains consumer behavior data from November 2019 for a major e-commerce multi-category store. It is a large dataset (5GB) taken from Kaggle: <https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store>

Columns

event-time: timestamp of the collected datapoint

event-type: view/cart/remove from cart/purchase depending on the customer action

product\_id: the product that is undergoing the event

category\_id: id corresponding to the category of the product

category\_code: code corresponding to the category of the product

brand: name of the brand 

price

user\_id

session\_id

**Tools Used**

1. PySpark
1. DataPrep
1. MatPlotLib
1. SparkML
1. Pandas
1. Kaggle Notebook

**Data Pre-Processing**

1. Missing Values: Rows carrying missing values were dropped.

![](Aspose.Words.89cdc07d-e501-4e7d-8ddd-6805ef010b67.001.png)

1. Duplicate values: Rows with duplicate values were also dropped.

![](Aspose.Words.89cdc07d-e501-4e7d-8ddd-6805ef010b67.002.png)

**Data Analysis and Visualization**

For Event-Type: View

![](Aspose.Words.89cdc07d-e501-4e7d-8ddd-6805ef010b67.003.png)

![](Aspose.Words.89cdc07d-e501-4e7d-8ddd-6805ef010b67.004.png)

![](Aspose.Words.89cdc07d-e501-4e7d-8ddd-6805ef010b67.005.png)

For Event-type: Cart

![](Aspose.Words.89cdc07d-e501-4e7d-8ddd-6805ef010b67.006.png)

![](Aspose.Words.89cdc07d-e501-4e7d-8ddd-6805ef010b67.007.png)

![](Aspose.Words.89cdc07d-e501-4e7d-8ddd-6805ef010b67.003.png)


For Event-type: Purchase

![](Aspose.Words.89cdc07d-e501-4e7d-8ddd-6805ef010b67.008.png)

![](Aspose.Words.89cdc07d-e501-4e7d-8ddd-6805ef010b67.009.png)

![](Aspose.Words.89cdc07d-e501-4e7d-8ddd-6805ef010b67.010.png)





