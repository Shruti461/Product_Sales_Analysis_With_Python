# Product_Sales_Analysis_With_Python
In this project I am Cleaning, Analysing to make data easily accessible of ease use
## Introduction
Every modern company that engages in online sales or maintains a specialized e-commerce website now aims to maximize its throughput in order to determine what precisely their clients need in order to increase their chances of sales.
### What is Sales Analysis?
For each product sold by your business, it is recommended that you perform a product sales analysis to compare the profit contribution of different products. Product sales analysis is a judgment on the market performance of a product.
Things To Consider before doing a Sales Analysis
i.) Understanding the Business Model
ii.) Problem we are trying to solve (Problem Analysis)
iii.) How it is and how is it going to be consumed by the consumer?
iv.) The economic impact of this project
v.) What type of decisions will our data drive?
vi.) Target in mind to quantify success of the project
## overview
This dataset gives us electronics sales data at Amazon. It contains user ratings for various electronics items sold, along with category of each item and time of sell.
Link to Data [here](https://www.kaggle.com/datasets/edusanketdk/electronics)

We will use Python libraries (Pandas, Numpy, Matplotlib & Seaborn) to analyse and answer business questions for sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. The dataset can be downloaded [here](https://www.kaggle.com/datasets/edusanketdk/electronics?select=electronics.csv). In this analysis, we will be using Jupyter Notebook.
## Tools used
To conduct the analysis i used Python 3, pandas through Jupyter Notebook
### Libraries used
1. Pandas
1. Numpy
1. Matplotlib 
1. Seaborn
## How to Execute
### STEP 1:
Exploratory Data Analysis [EDA]
This is the process by which we shall critically perform initial investigations of the data we have to discover patterns, to spot anomalies, test hypothesis and to check assumptions with the help of summary statistics and graphical representations.
To start with, we import libraries we are going to use. In this case being Pandas, Numpy, Matplotlib and Seaborn.
Then we load the dataset as shown below.
![p1](https://github.com/Shruti461/Product_Sales_Analysis_With_Python/assets/142620672/3cace408-d9f8-4fff-ac85-34369186264d)

To take a look of the first five rows we use the pandas function “ .head()”. Similarly “.tail()” returns last five observations of the data set.
![p2](https://github.com/Shruti461/Product_Sales_Analysis_With_Python/assets/142620672/61821aa9-2cd0-41dc-9f06-500aef6fd4ca)

To know the total number of rows and columns in the data set we use “.shape” as shown below.
![p3](https://github.com/Shruti461/Product_Sales_Analysis_With_Python/assets/142620672/a2fc5572-bca6-4a30-87d4-fa35f7dc35e8)

Dataset comprises of 1,292,954 observations and 10 characteristics.
Out of which one is dependent variable and rest 9 are independent variables

It is also a good practice to know the columns and their corresponding data types, along with finding whether they contain null values or not.
![p4](https://github.com/Shruti461/Product_Sales_Analysis_With_Python/assets/142620672/4f1111a4-6a6d-45cb-862d-93cbd21b74e7)
No Variable column has null/missing values
We can see that the dataset contains 5 columns and 10000 rows.

To get a better understanding of the dataset, we can also see the statistical summary of the dataset using the function “.describe()”.
![p5](https://github.com/Shruti461/Product_Sales_Analysis_With_Python/assets/142620672/ed549151-5986-4685-9fc5-905547cdb468)

We can also see the number of unique users and items in the dataset.
![p6](https://github.com/Shruti461/Product_Sales_Analysis_With_Python/assets/142620672/8288394f-a133-43bf-9ddd-4a7aaa565dcf)

Some of the reasons are listed below:
Past data might get corrupted due to improper maintenance.
Observations are not recorded for certain fields due to some reasons. There might be a failure in recording the values due to human error.
The user has not provided the values intentionally.
Dealing With Missing Values
There can be multiple reasons why certain values are missing from the data
![p7](https://github.com/Shruti461/Product_Sales_Analysis_With_Python/assets/142620672/8837d410-f71a-4900-b611-d0ca9edebaca)






