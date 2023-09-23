# Maven-Marketing-Report with Excel
## Introduction
I participated in a challenge on Twitter themed “LearnDataAnalyticsWithTina” organized by Tina Okonkwo. This was a project after the successful completion of the excel course.

## The dataset
The dataset was provided by Tina Okonkwo, it was originally downloaded as a zipped file of 55KB containing the raw data, data dictionary and business questions to be answered. The dataset contains of 2240 rows and 28 columns with the following details: Customer_ID, product types (wines, meat, fish, gold, sweet and fruits); purchase channels, income, age, marital status amongst others information. 

## Objective
The objective is to analyze the dataset using Excel.
To provide answers to the following Business questions using pivot Table and dashboard
-	What factors are significantly related to the number of web purchases?
-	Which marketing campaign was the most successful?
-	What does the average customer look like?
-	Which products are performing best?
-	Which channels are underperforming?

## Data Transformation:
The following was done:
-	The dataset was made dynamic by inserting the data in a table; and giving a name to the table Maven Marketing.  The advantage of this is that if dataset is updated, it will automatically become part of the table. Also it makes it easier to sort and filter the data and most especially to transform and clean the data.
-	Check for duplicates, luckily this dataset does not contain any duplicate.
-	Remove the outliers in the Year birth column (1893; 1899 and1900)
-	Correct data types
-	Add a new column to create age bracket using the “IF Statement”: Less than 30: Twenties; greater than or equal to 30: Thirties; Greater than or equal to 40: Forties; Greater than or equal to 50: Fifties; Greater than or equal to 60: Old and 70 & Above : Senior.
-	Add some new columns for Total Sales; Total Orders and Income group using the IF Statement.

## Analysis and Visualization:  
This was done using Pivot Tables, charts and dashboard.  Data was visualized using charts like bar chart, clustered column chart, line chart, sunburst and treemap. 
![](https://github.com/Mayreeobi/Maven-Marketing-Report/blob/main/maven1.png)

![](https://github.com/Mayreeobi/Maven-Marketing-Report/blob/main/maven2.png)

## Insights
1. Maven  Store has a customer based of  2,240 with an average income of $52,247.
2 The best performing product is Wine with a sales record of $680,816  while the least is  Fruits $58,917
3. The best channel of purchase is the Store  with an order of 12,970;  followed by Website (9,150) and lastly Catlogue with a figure of 5,963 .
4. Website purchase was significantly high as  the cutstomer that made purchase through that channel are tech savy.
5. The most succesful accepted campaign was Campaign 4; and Campaigns 3 and 5 had the same number of acceptance.
6. Spain has the highest sales of $662,220, while Married made the highest sales.

## Recommendations
1. More wines should be made available, as it was the best performing product.
2. To improve the underperforming channel, customers should be given incentives by way of coupons and free delivery for orders placed within certain locations.
3. More marketing campaign should be implemented, as there have been positive and significant responses from customers.
4. Marketing team conduct a research on the previous  fruits'  purchases to ascertain, the most perferred type of fruit bought by customer and  stock more of the fruits. Also inorder to encourage the purchase of fruits; the fruits should be discounted on certain days of the week.
5. Customer support team should be commended as the rate of complaints has reduced to (3) complaints when compared to the previous year.
