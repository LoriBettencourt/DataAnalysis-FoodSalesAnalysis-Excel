# Food Sales Analysis

## Scenario
The "Snack Love" food company has tracked its sales order data 
* for each food and food type category (bars, cookies, crackers and snacks) 
* by month of year 
* in its four distribution cities (Boston, Los Angeles, New York and San Diego) 
* for the years 2020 and 2021  

They have asked us to look at product performance during this two-year span.

## Business Task
We have been asked specifically to look for the following and deliver suggestions based on our findings: 
1) Food or food types that have underperformed for two consecutive years
2) Food or food types with a significant decrease in sales from 2020 to 2021.

# Response to Business Task
Note: Snack Love has a total of 9 products.  
1. & 2. Underperforming foods and sales decreases
* Even though Pretzel Snacks are the product with the highest growth from 2020 to 2021, the sales dollar amount for 2021 is only $500.85 of the $15,337 total sales for the year. This accounts for just 3% of sales for 2021 out of all 9 products.     
* Similarly, Banana Bars sales in 2021 increased by 63%, but this only makes up 0.7% of sales for the year.   
* Potato Chip Snack sales are 2.6% of the total sales and dropped 69% in 2021. 
* Whole Wheat Cracker sales are 5.5% of total sales and dropped 67% in 2021. Note, however, that Whole Wheat is the only cracker flavor, so this data is about the entire food type category.
* Cracker and Snack food types consist of 3 of our 9 products and only 11% of sales in 2021.

Suggestions:
1) Pretzel Snacks already carry the second highest price of all food items at $3.15. Raising the price does not seem like a good option. We should consider:  
a) Lowering the price to see if sales improve.  
b) Contact and/or survey customers in New York, Los Angeles, and San Diego to determine why they have not ordered this item.  
c) Consider changing the recipe.  
d) Ditch this product altogether.  

2) Banana Bar sales are so low that dropping this product altogether might be the best option and perhaps consider a replacement flavor.

3) Potato Chip Snacks  
a) Try a new flavor or add flavors  
b) Consider a new marketing campaign  
c) Discontinue item

4) Wheat Cracker Snacks: We can't realistically consider dropping numerous products at one time, but this one is on watch. We may want to look to some of the above suggestions after deciding how we will move forward with the other underperforming products.

5) Cookies have been our best-selling item both years with sales increasing in 2021.  
a) Conduct a survey in current customer cities for other potential cookie flavors.  
b) Create and market additional cookie flavors.  

6) Initiate contact to customers in additional cities with Cookies and Bars as our primary and secondary products to market.

## Suggestions For Future Analysis  
* Continue collecting data for observations  
* Include profit in future data collection
* Let BI tool handle more of that analysis calculations required to provide solutions for business task.  

## Data
Data was sourced from [Contextures](https://www.contextures.com/index.html) and downloaded from their [Sample Data](https://www.contextures.com/xlsampledata01.html) page. 
This data set contains 244 sales order data records for Snack Love's food items and cities over the time period to be analyzed. The data is stored in long format. We consider the data to be first-party data, with a complete sales order history and therefore reliable and comprehensive. The 2-year time period could be considered a limitation, but Snack Love may a young company eager to make informed, data-driven decisions early. The data reflects the last two calendar years, so it is timely.  
The following metadata information is quoted from the [Contextures](https://www.contextures.com/index.html) [Sample Data](https://www.contextures.com/xlsampledata01.html) page.

**Metadata**  
This sample file has food sales data, from an imaginary food company.

There are 8 columns of data, including 1 column with a calculation.
There are 244 rows of data in the food sales table.
Each row shows the following fields:

OrderDate: Date the order was placed  
Region: geographic region where order will be shipped  
City: city where order will be shipped  
Category: product category - Bars, Cookies, Crackers or Snacks  
Product: product name  
Quantity: number of units ordered  
UnitPrice: product selling price per unit  
TotalPrice: total price of order - calculation - Quantity x UnitPrice 

## Visualizations
Explainations of visualizations can be reviewed at [Visualizations.md](/Visualizations.md)

## Resources
[Contextures](https://www.contextures.com/index.html)  
[Contextures Sample Data](https://www.contextures.com/xlsampledata01.html)  
[Coursera](https://www.coursera.org/)  
[Google Data Analytics Certificate Course](https://www.coursera.org/professional-certificates/google-data-analytics?utm_source=gg&utm_medium=sem&utm_campaign=15-GoogleDataAnalytics-US&utm_content=B2C&campaignid=12504215975&adgroupid=122709142687&device=c&keyword=coursera%20data%20analytics%20course&matchtype=b&network=g&devicemodel=&adpostion=&creativeid=504570191916&hide_mobile_promo&gclid=Cj0KCQjw94WZBhDtARIsAKxWG--aGc_mpu7WTeU8sHtAVT4D9k79qOSJOCdgcl3hVUqPH2zR1B2j8acaAovsEALw_wcB)   
[How to build Interactive Excel Dashboards that Update with ONE CLICK! (YouTube video by MyOnlineTrainingHub)](https://www.youtube.com/watch?v=K74_FNnlIF8&list=PLdeA_5rmA1Ecl1MnWUsyuV3IjiPSOqbU7&index=3)  
[Secrets to Building Excel Dashboards in Under 15 Minutes! (YouTube video by MyOnlineTrainingHub)](https://www.youtube.com/watch?v=9p6tWCHbtPQ&list=PLdeA_5rmA1Ecl1MnWUsyuV3IjiPSOqbU7&index=1&t=571s)  
[How to Build Excel Interactive Dashboards (YouTube video by Kevin Stratvert)](https://www.youtube.com/watch?v=MTlQvyNQ3PM&list=PLdeA_5rmA1Ecl1MnWUsyuV3IjiPSOqbU7&index=2&t=480s)  
[Bellabeat Case Study by Lori Bettencourt](https://github.com/LoriBettencourt/DataAnalysis-BellabeatCaseStudy)
