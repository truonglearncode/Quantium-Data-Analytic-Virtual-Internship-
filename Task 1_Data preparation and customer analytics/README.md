# TASK 1: DATA PREPARATION AND CUSTOMER ANALYTICS
## Table of Content
 - [Overview](#overview)
 - [Background Information](#background-info)
 - [Task Information](#task-info)
 - [My Solutions](#solutions)
 - [Key Finding and Recommendation](#F&R)
## Task Overview <a class = 'anchor' id = 'overview'></a>
**What I'll learn**
- Understand how to examine and clean transaction and customer data.
- Learn to identify customer segments based on purchasing behavior.
- Gain experience in creating charts and graphs to present data insights.
- Learn how to derive commercial recommendations from data analysis.

**What I'll do**
- Analyze transaction and customer data to identify trends and inconsistencies. 
- Develop metrics and examine sales drivers to gain insights into overall sales performance. 
- Create visualizations and prepare findings to formulate a clear recommendation for the client's strategy.
## Background Information <a class = 'anchor' id = 'background-info'></a>
You are part of Quantium’s retail analytics team and have been approached by your client, the Category Manager for Chips, who wants to better understand the types of customers who purchase Chips and their purchasing behaviour within the region.

The insights from your analysis will feed into the supermarket’s strategic plan for the chip category in the next half year.

*Main Tasks*

`Examine transaction data` – look for inconsistencies, missing data across the data set, outliers, correctly identified category items, numeric data across all tables.

`Examine customer data` – check for similar issues in the customer data, look for nulls and when you are happy merge the transaction and customer data together

`Data analysis and customer segments` – make sure you define the metrics – look at total sales, drivers of sales, where the highest sales are coming from etc. Explore the data, create charts and graphs as well as noting any interesting trends and/or insights.

`Deep dive into customer segments`   – define your recommendation from your insights, determine which segments we should be targeting
## Task Information <a class = 'anchor' id = 'task-info'></a>
We need to present a strategic recommendation to Julia that is supported by data which she can then use for the upcoming category review. However, to do so, we need to analyse the data to understand the current `purchasing trends` and `behaviours`. The client is particularly interested in `customer segments` and their `chip purchasing behaviour`. Consider what metrics would help describe the customers’ purchasing behaviour.  

Begin performing high-level data checks such as:

- Creating and interpreting high-level summaries of the data
- Finding outliers and removing these (if applicable)
- Checking data formats and correcting (if applicable)

You will also want to derive extra features such as `pack size` and `brand name` from the data and define metrics of interest to enable you to draw insights on who spends on chips and what drives spends for each customer segment. Remember, our end goal is to form a strategy based on the findings to provide a clear recommendation to Julia the Category Manager so make sure your insights can have a commercial application.

`LIFESTAGE`: Customer attribute that identifies whether a customer has a family or not and what point in life they are at e.g. are their children in pre-school/primary/secondary school.

`PREMIUM_CUSTOMER`: Customer segmentation used to differentiate shoppers by the price point of products they buy and the types of products they buy. It is used to identify whether customers may spend more for quality or brand or whether they will purchase the cheapest options.
## Solutions <a class = 'anchor' id = 'solutions'></a>

View my solution in python here: [Task 1_solution.ipynb](https://github.com/truonglearncode/Quantium-Data-Analytic-Virtual-Internship-/blob/main/Task%201_Data%20preparation%20and%20customer%20analytics/Task%201_Solution.ipynb)

## Key Finding and Recommendation <a class = 'anchor' id = 'F&R'></a>

Across all customer types, `BUDGET` and `MAINSTREAM` customer consistently have the highest total sales, indicating they are the most valuable segment. In addition, need to keep `PREMIUM` customers as loyal customer and engage them to core customer in future

3 Highest sale by customer segment:
- OLD FAMILIES - BUDGET
- YOUNG SINGLE/COUPLES - MAINSTREAM
- RETIREES - MAINSTREAM

Why 3 customer segment get highest sales
Average price per customer transaction is higher than another customer it around 7.0 and times buying chip are very high it over 19000 times. This thing make 3 highest sale segment really important to keep them buying chip and convert them to loyal customer by direct them with loyal customer program or engage them buy more chip on single transaction by addition gift, voucher, on future marketing stategy

Almost customer really like chip with pack size is 175 follow by 150 and 134. I think it enough for almost customer segment from youngest to oldest. My opinions is optimizing package size in future with 3 main size is 175, 150, 134 and optional size for special order with special price for each order. It can be helpful because we will focus on 3 size to improve customer experience, package design, product R&D, ...

3 Brand each customer segment favorite is familar. It belong to Kettle, Smith and Doritos but YOUNG SINGLES/COUPLES - Mainstream something different in top 3 it belong to Pringles in top 3. In this case 4 popular chip brand make 80% revenue of chain and another brand dont sell enough well make inventory item and inventory cost is so high. In the future necessery thing we can do right now is contact with brand dont sell well to deal a discount price or advertiment for my customer. If this ways dont help this brand stand out with my customer i think we need remove this brand of my supplier

Customer segment distribute familar from monday to sunday. Some segment want to visit in head of week, another segment raise in middle of week, some segment want to enjoy my chip at the end of week. Every day of week almost crownd so make sure every store of cip chain have enough employees, machines, matirial, iridient,... Encorage all employees in each shiff make an effort for work to give customer good experience every time they visit the store. It seem be same with any month in the year. Take note and prepare any thing good in each month 

