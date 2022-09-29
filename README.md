## **Initial Analysis: Will take a beat and revisit with fresh eyes, check for typos, and double-check calculations and analysis.** 

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
* Even though Pretzel Snacks are the product with the highest growth from 2020 to 2021, the sales dollar amount for 2021 is only $501 of the $15,337 total sales for the year. This accounts for just 3% of sales for 2021 out of all 9 products.   
* Similarly, Banana Bars sales in 2021 increased by 63%, but this only makes up 0.7% of sales for the year.  
* Potato Chip Snack sales are 2.6% of the total sales and dropped 69% in 2021.
* Whole Wheat Cracker sales are 5.5% of total sales and dropped 67% in 2021. Note, however, that Whole Wheat is the only flavor of cracker so this data is about the entire food type category.
* Cracker and Snack food types consist of 3 of our 9 products and only 11% of sales in 2021.

Suggestions:
1) Pretzel Snacks already carry the second highest price of all food items at $3.15. Raising the price does not seem like a good option. We should consider:  
a) Lowering the price to see if sales improve.  
b) Contact and/or survey customers in New York, Los Angeles and San Diego to determine why they have not ordered this item.  
c) Consider changing the recipe.  
d) Ditch this product altogether.  

2) Banana Bar sales are so low that dropping this product altogether might be the best option and perhaps consider a replacement flavor.

3) Potato Chip Snacks  
a) Try a new flavor or add flavors  
b) Consider a new marketing campaign  
c) Discontinue item

4) Wheat Cracker Snacks: We can't realistically consider dropping numerous products at one time, but this one is on watch. We may want to look to some of the above suggestions after deciding how we will move forward with the other underperforming products.

5) Cookies have been our best selling item both years with sales increasing in 2021.  
a) Conduct a survey in current customer cities for other potential cookie flavors.  
b) Create and market additional cookie flavors.  

6) Open up contacts to customers in additional cities with Cookies and Bars as our primary and secondary products to market.


## Data
Data was sourced from [Contextures](https://www.contextures.com/index.html) and downloaded from their [Sample Data](https://www.contextures.com/xlsampledata01.html) page. 
This data set contains 244 sales order data records for Snack Love's food items and cities over the time period to be analyzed. The data is stored in long format. We consider the data to be first-party data, with a complete sales order history and therefore reliable and comprehensive. The 2-year time period could be considered a limitation but Snack Love may a young company eager to make informed, data-driven decisions early. The data reflects the last two calendar years, so it is timely.  
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
Perhaps more visualizations than necessary, but I was curious to try them and see where they led me. In the future, I would consider omitting the "Sales by City and Food Type" and "Sales by Month of Year" charts.

### **Notes**
* Other than the "Sales 2021 Over 2020" bar chart, all visualizations can show either single year or multi-year data using the date slicer buttons.  
* Other than the "Sales % by Food Type" and "Quantity % by Food Type" pie charts and the sparklines in the  "Sales Totals and Trends by City" chart, all visualizations will show information on any combination of Bar, Cookies, Crackers, and Snacks.
* Other than the "Sales by City" and "Sales by City and Food Type" bar graphs, all visualizations will show information on any city combinations of Boston, Los Angeles, New York, and San Diego.

### **Bar Charts and Stacked Bar Charts**  
### Yearly Sales:  
Shows sales by year in total or filtered by food types and/or cities.

* Observations: Total sales in 2021 were $2652 lower than in 2020, which is nearly a 15% decrease. 

### Yearly Sales (With Food Type):  
Shows sales by selected food types, years, and cities. A stacked bar shows the division of sales by food type in each column.

* Observations: Total cookie sales increased in 2021 but all other food types decreased.

### Sales by City:
Shows the total sales by city based on years and food types selected. Again, a stacked bar shows the division of sales by food type in each column.

* Observations: For all four cities, when both years are in view, cookie and bar sales came in first and second, respectively. Then, crackers beat out snacks in Boston; they were tied in San Diego; and snack sales were slightly over cracker sales in New York and Los Angeles.

    Sales orders in Boston are higher for both years and for all food types, except for snack sales in Los Angeles in 2020.

### Sales by City and Food Type:
Shows sales in all four cities by selected food types and years.

* Observations: This visualization is very similar to "Sales by City" but provides the ability to show food type information side-by-side for perspective.

### Sales by Item:
Shows the sales of each item by selected years, food types, and cities.

* Observations: Carrot Bars and Oatmeal Raisin Cookies have the best sales overall and during individual years when all cities are considered. Pretzel Snacks and Banana Bars have negligible sales across cities in 2020. Pretzel sales increase from 2020 to 2021 by 489% rising from $85.05 to $500.85, while Potato Chip Snacks fell 69% decreasing from $1256.97 to $394.80. 

When we filter by individual city, we notice that all cities order Potato Chip Snacks, but Boston is the only city to order Pretzel Snacks in both years.

Since Pretzel Snack sales were so low to begin with, this high percentage increase does not do much to bring the 2021 order sales close to those of 2020.

### Sales by Month of Year:  
Shows sales per month of year and further shown by year for the selected food types and cities.

* Observations: On this bar chart, we can see that sales by month of year also varies between 2020 and 2021. Overall, however, sales orders in 2020 were greater than 2021 for 9 our of 12 months when we have all data observations considered.

### Sales 2021 over 2020:
Shows the relative performance of each food item by selected food types and cities from 2020 to 2021.

* Observations: Considering all sales for all cities, 
    Potato Chip Snacks at $395 was a decrease of 69%. 2021 Sales of Total products: 2.6% = [395/(15,337)*100])
    Whole Wheat Crackers at $838 was a decrease of 67%. 2021 Sales of Total products: 5.5% = [838/(15,337)*100]) 
    Carrot Bars sales were $3064 which was a decrease of 30% 
    from 2020 to 2021. 
    
    Let's keep in mind here that we noted from the "Sales by Item" chart that Carrot bars are still a top two performer regardless of year.  

    Pretzel Snacks had the highest increase, as noted when looking at different filter in "Sales by Item" chart, but recall that this accounts for about $501 in sales (3% = [501/(15,337)*100]).  

    Sales of Banana Bars had the second highest increase at 63%, but looking at the "Sales by Item" chart, this only represents $110 in sales for 2021 (0.7% = [110/(15,337)*100]).

### Food Type Sales by Month of Year:  
Shows sales by selected food types each month of the selected years for selected cities. Items with the greatest sales are on the bottom of each month's aggregation and decrease as you scan higher in the given month.

* Observations: There is a wide variance in sales order revenue across each food type by month and year.

### **Pie Charts**  
### Sales % by Food Type:
Shows the percentage of sales orders in dollars for each food type by selected year and city.

### Quantity % by Food Type:
Shows the percentage of the quantity ordered for each food type by selected year and city.

* Pie Chart Observations: Staying consistent with insights derived from the "Sales by City" stacked bar chart, when all cities and both years are considered, cookies show the highest sales dollars (52%) and also the highest quantity (48%) of all food types sold, with bars behind in second place (Sales: 31% Quantity: 38%). This is true in both 2020 and 2021, and so is naturally the case overall.  
    Crackers make up 10% of sales and 6% of quantity sold while snacks account for 7% of sales and 8% of quantity sold.

### **Bar Chart with Accompanying Sparklines**  
### Sales Totals and Trends by City:
Sales and Sales Bar - Column values will change dynamically as years and food types are selected.

* Observations: We see as we did in the "Sales by City" chart that with all food items considered, Boston has been consistently in first place for sales (40% = [13266/(17989+15,337)*100]). New York and Los Angeles are in second and third places respectively in 2020 but swap positions in 2021. San Diego remains in 4th place from year to year.

    All Product Trends - Shows sparkline for all products for selected years.

Cookies, Bars, Crackers, and Snacks sparklines - Shows sales trends for selected years and will also isolate selected cities.

* Sparkline Observations: Consistent again with "Food Type Sales by Month of Year", sales orders by month are rather sporadic.

### **Line Graph**  
Sales by Food Type:
Shows the sales of each food type by selected years, food types, and years.

* Observations: The line graph shows agreement with the "Food Type Sales by Month of Year" graph in that sales of each food type definitely vary by month, but we can see here that cookie and bar sales are generally higher than crackers and snacks whether you consider 2020 and 2021 together or apart.

## Suggestions For Future Analysis  
Continue collecting data for observations  
Include profit in future data collection

## Resources
[Contextures](https://www.contextures.com/index.html)  
[Contextures Sample Data](https://www.contextures.com/xlsampledata01.html)  
[Coursera](https://www.coursera.org/)  
[Google Data Analytics Certificate Course](https://www.coursera.org/professional-certificates/google-data-analytics?utm_source=gg&utm_medium=sem&utm_campaign=15-GoogleDataAnalytics-US&utm_content=B2C&campaignid=12504215975&adgroupid=122709142687&device=c&keyword=coursera%20data%20analytics%20course&matchtype=b&network=g&devicemodel=&adpostion=&creativeid=504570191916&hide_mobile_promo&gclid=Cj0KCQjw94WZBhDtARIsAKxWG--aGc_mpu7WTeU8sHtAVT4D9k79qOSJOCdgcl3hVUqPH2zR1B2j8acaAovsEALw_wcB)   
[How to build Interactive Excel Dashboards that Update with ONE CLICK! (YouTube video by MyOnlineTrainingHub)](https://www.youtube.com/watch?v=K74_FNnlIF8&list=PLdeA_5rmA1Ecl1MnWUsyuV3IjiPSOqbU7&index=3)  
[Secrets to Building Excel Dashboards in Under 15 Minutes! (YouTube video by MyOnlineTrainingHub)](https://www.youtube.com/watch?v=9p6tWCHbtPQ&list=PLdeA_5rmA1Ecl1MnWUsyuV3IjiPSOqbU7&index=1&t=571s)  
[How to Build Excel Interactive Dashboards (YouTube video by Kevin Stratvert)](https://www.youtube.com/watch?v=MTlQvyNQ3PM&list=PLdeA_5rmA1Ecl1MnWUsyuV3IjiPSOqbU7&index=2&t=480s)  
[Bellabeat Case Study by Lori Bettencourt](https://github.com/LoriBettencourt/DataAnalysis-BellabeatCaseStudy)
