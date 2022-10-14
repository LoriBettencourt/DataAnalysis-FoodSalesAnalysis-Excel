## Visualizations - Excel Dashboard
Perhaps more visualizations than necessary, but I was curious to try them and see where they led me. In the future, I would consider omitting the "Sales by City and Food Type" and "Sales by Month of Year" charts.

### **Notes**
* Other than the "Sales 2021 Over 2020" bar chart, all visualizations can show either single year or multi-year data using the date slicer buttons.  
* Other than the "Sales % by Food Type" and "Quantity % by Food Type" pie charts and the sparklines in the  "Sales Totals and Trends by City" chart, all visualizations will show information on any combination of Bar, Cookies, Crackers, and Snacks.
* Other than the "Sales by City" and "Sales by City and Food Type" bar graphs, all visualizations will show information on any city combinations of Boston, Los Angeles, New York, and San Diego.

### **Bar Charts and Stacked Bar Charts**  
### Yearly Sales:  
Shows sales by year in total or filtered by food types and/or cities.

* Observations: Total sales in 2021 were $2652 lower than in 2020, which is nearly a 15% decrease. (ABS(15337 - 17989)/17989 * 100)

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

* Observations: Carrot Bars and Oatmeal Raisin Cookies have the best sales overall and during individual years when all cities are considered. Pretzel Snacks and Banana Bars have negligible sales across cities in 2020. Pretzel sales increase from 2020 to 2021 by 489% [ABS(85 - 500.85) / 85 * 100] rising from $85.05 to $500.85, while Potato Chip Snacks fell 69% decreasing from $1256.97 to $394.80 [ABS(1256.97 - 394.80) / 1256.97 * 100]. 

When we filter by individual city, we notice that all cities order Potato Chip Snacks, but Boston is the only city to order Pretzel Snacks in both years.

Since Pretzel Snack sales were so low to begin with, this high percentage increase does not do much to bring the 2021 order sales close to those of 2020.

### Sales by Month of Year:  
Shows sales per month of year and further shown by year for the selected food types and cities.

* Observations: On this bar chart, we can see that sales by month of year also varies between 2020 and 2021. Overall, however, sales orders in 2020 were greater than 2021 for 9 our of 12 months when we have all data observations considered.

### Sales 2021 over 2020:
Shows the relative performance of each food item by selected food types and cities from 2020 to 2021.

* Observations: Considering all sales for all cities,  
    Potato Chip Snacks at $395 was a decrease of 69%. 2021 Percent of Total product sales: 2.6% = [395 / (15337) * 100])  
    Whole Wheat Crackers at $838 was a decrease of 67%. 2021 percent of Total product sales: 5.5% = [838 / (15337) * 100])  
    Carrot Bars sales were $3064 which was a decrease of 30% [ABS(4347 - 3064) / 4347 * 100] from 2020 to 2021. 
    
    Let's keep in mind here that we noted from the "Sales by Item" chart that Carrot bars are still a top two performer regardless of year.  

    Pretzel Snacks had the highest increase, as noted when looking at different filter in "Sales by Item" chart, but recall that this accounts for about 3%  of sales [501 / (15337) * 100].  

    Sales of Banana Bars had the second highest increase at 63%, but looking at the "Sales by Item" chart, this only represents $110 in sales for 2021 (0.7% = [110 / (15337) * 100]).

### Food Type Sales by Month of Year:  
Shows sales by selected food types each month of the selected years for selected cities. Items with the greatest sales are on the bottom of each month's aggregation and decrease as you scan higher in the given month.

* Observations: There is a wide variance in sales order revenue across each food type by month and year.

### **Pie Charts**  
### Sales % by Food Type:
Shows the percentage of sales orders in dollars for each food type by selected year and city.

### Quantity % by Food Type:
Shows the percentage of the quantity ordered for each food type by selected year and city.

* Pie Chart Observations: Staying consistent with insights derived from the "Sales by City" stacked bar chart, when all cities and both years are considered, cookies show the highest sales dollars (52%) and also the highest quantity (48%) of all food types sold, with Bars behind in second place (Sales: 31% Quantity: 38%). This is true in both 2020 and 2021, and so is naturally the case overall.  
    Crackers make up 10% of sales and 6% of quantity sold while snacks account for 7% of sales and 8% of quantity sold.

### **Bar Chart with Accompanying Sparklines**  
### Sales Totals and Trends by City:
Sales and Sales Bar - Column values will change dynamically as years and food types are selected.

* Observations: We see as we did in the "Sales by City" chart that with all food items considered, Boston has been consistently in first place for total sales spanning 2020 and 2021 (40% = [(7243 + 6023) / (17989 + 15337) * 100]). New York and Los Angeles are in second and third places respectively in 2020 but swap positions in 2021. San Diego remains in 4th place from year to year.

    All Product Trends - Shows sparkline for all products for selected years.

Cookies, Bars, Crackers, and Snacks sparklines - Shows sales trends for selected years and will also isolate selected cities.

* Sparkline Observations: Consistent again with "Food Type Sales by Month of Year", sales orders by month are rather sporadic.

### **Line Graph**  
Sales by Food Type:
Shows the sales of each food type by selected years, food types, and years.

* Observations: The line graph shows agreement with the "Food Type Sales by Month of Year" graph in that sales of each food type definitely vary by month, but we can see here that cookie and bar sales are generally higher than crackers and snacks whether you consider 2020 and 2021 together or apart.