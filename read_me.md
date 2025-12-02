1. Data Loading and Profiling
Below are the profilings each dataset:

![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
It can be seen that all data type is already based on the requirements and there is no null value.

Below is the anomaly summary:
![alt text](image-4.png)
It can be seen that there is no anomaly with the data

2. Data cleaning and standardization
Below are the standarsization text using trim and lower for column city in user data and category for order items data
![alt text](image-5.png)

You can see below the comparison before and after deduplication in primary key in each dataset
![alt text](image-6.png)
You can see that no duplicate in these datasets

3. Data enrichment and feature engineering
Below the new column called total_item_value in
![alt text](image-7.png)

Below the order value flag column 
![alt text](image-8.png)

Below the table for the tenure segment,
![alt text](image-9.png)

4. Join and Aggregation
Below the fact table that is a join table between all 4 tables
![alt text](image-10.png)

Below the aggregation for daily gmv per category, daily orders per category, and daily items sold,
![alt text](image-11.png)

Below the aggregation for total gmv per city, AOV per city, and total unique per customer per city,
![alt text](image-12.png)

Below the aggregation for rank category per city based on gmv per city per category,
![alt text](image-13.png)

5. Windows Analytics and Insight
Below is the window function to know spending per user:
![alt text](image-14.png)

Below gmv daily and cumulative gmv daily per order date:
![alt text](image-15.png)

Below is the top 10 biggest spender,
![alt text](image-16.png)



