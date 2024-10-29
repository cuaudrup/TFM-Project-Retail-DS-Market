# Task 1: Global Analysis.
Initially we received three tables with separate information:
- File 1. daily_calendar_with_events.csv. This table in .csv format contains date and time information.
- File 2. item_prices. This table in .csv format contains information about the prices of each product in each store for each week of the year.
- File 3. item_sales.csv. This table contains information on the number of products sold per day in each store.

The first step is to create a single table with the sales, prices and date information. Finally, we are left with a table of 58327370 recorded in a single table.
Image 1.

The next step is to export this data as a .csv file and load it into PowerBI to begin our data analysis and business understanding. Dividing our analysis into the following parts:
- GLobal vision.
- Vision by category.
- Vision by department.
- Vision by region and store.

## Global Vision:
We created a first dashboard with all the data that allows us to understand the business data from a global perspective. For the first KPIs regarding the company's sales trends, we took 2015 as a benchmark and compared it to the previous year to gain the following insights.
- As KPIs we have different insights:
  - Sales with $52.32m and the comparison with the previous year of $46.58m (+12.33%).
  - Items sold with 13.8 M, and its comparison with the previous year at 13.09 M (+5.43%).
  - Average sale per item with 3.79 $, and its comparison with the previous year at 3.56 $ (+6.55%).
  - Sales per day with $143,349m, and its comparison with the previous year at $127,611m (+12.33%).
 
  Image 2

These KPIs are valuable for the company to monitor and understand future developments. The data shows a positive trend, as illustrated in several graphs.

A line graph is used to track the evolution of sales, items sold, and average price over time. This graph has been set up to compare each month with the same month from the previous year, allowing us to observe the annual trend. From this, we can see that July and August consistently show higher sales percentages, driven by an increase in the number of items sold, even though the average price during these months is lower. Conversely, at the beginning and end of the year, we see a rise in the average price, despite lower sales volumes, particularly at the start of the year.

Additionally, we have represented these same metrics in bar charts, grouped by quarter, which further confirm these insights.

Image 3.

Next, we zoom in on the sales performance of each category.

## Vision by Category.
After dumping the data into the PBI and filtering by category, we see that there are 3 different categories
1. Accessories.
2. Home & Garden.
3. Supermarket.

To analyse each category, we have used maps to show the KPIs compared to the previous year, as we did in the global view. In addition, we have added line graphs to show the trend over the years for both number of items sold and profit, where you can see the positive trend over the years.

Focusing by category in 2015 compared to the previous year:
- Supermarket accounts for 56% of sales, with an average price of $3.11 (up 5.6% year-on-year), a daily turnover of $76,917 and 9 million items sold.
  Image 4
- Home&Garden represents 30% of sales, with an average price of $4.83 (down 0.55% year-on-year), a daily turnover of 45 k$ and 3.4 million items sold.
45k$ per day and 3.4 million items sold.
  Image 5
- Accessories, which accounted for a further 14%, is the category with a higher average price of $5.64, but with a lower daily turnover of $21,546, due to the low number of units sold (1.39 million).
  Image 6

## Vision by Department.
The three product categories are further subdivided into departments. So we have seven departments.
1. Accessories 1.
2. Accessories 2.
3. Home & Garden 1.
4. Home & Garden 2.
5. Supermarket 1.
6. Supermarket 2.
7. Supermarket 3.

In order to analyse the departments, we filtered them by category and analysed them in the same structure as we did when studying the behaviour of the categories, taking 2015 as a reference year. 

Firstly, within the Accessories category. We have that Accessories 1 represents 94% of sales with a higher number of units sold and with a higher average price. On the other hand, Accessories 2 shows a decrease in sales price compared to the previous year, but a strong increase in the number of items sold (+23.5% compared to the previous year).
Image 7

Applying the Home & Garden category filter, we see that Home & Garden 1 represents 74.4% of sales. With an average price of $4.55, and a significant sales trend (18% more than the previous year). On the other hand, Home & Garden 2 represents 25.6% of sales with a highly seasonal behaviour within the year, although with a similar average ticket, it has much less items sold.
Image 8

Within the Supermarket category, Supermarket 3 accounts for 66% of sales, despite the fact that the number of items sold, 6.22 million, fell by 5% last year. On the other hand, the turnover of this department has remained practically the same thanks to an increase in the price of its products of almost 5%. Supermarket 2, which accounts for 22% of sales, has seen a 22% increase in turnover to $7.04 million and an 18% increase in sales, all with a price increase of only 3.5%. Finally, Supermarket 1, representing only 12% of sales, has a 13% increase in turnover and a 10% increase in sales, with only a 2.5% increase in price.
Image 9.

## Vision by Region and Store.
In this section, we see the data broken down by the following 3 regions:
- New York: represents 44.9% of revenue.
- Boston: represents 28.7% of revenue.
- Philadelphia: 26.4% of revenue.

In order to do the analysis by region and store, we have used two line graphs, one to see the evolution of the number of items sold over time and another to see the revenue. We have also added two tables, one to study the average price of products over the years and the other to see the average daily revenue depending on the day of the week. Finally, we have a heat map of the economic level of the counties in each region.

We can see that New York and Boston maintain this seasonality in the summer when sales increase, but Philadelphia does not. On the other hand, the average price has increased over the years in all regions, but more so in Boston and New York. The days of the week with the highest sales tend to be weekends, with Sunday being the busiest day, followed closely by Saturday.

Image region

In terms of analysis by branch, we have the following.

In Boston, we found three stores with very similar sales percentages:

- Roxbury at 37.9%
- Back Bay at 33.9%
- South End at 29.2%

The sales trend for these stores is positive, primarily due to Back Bay and an increase in item prices, as the trend in units sold remains relatively constant. In Roxbury, however, while there is a positive sales trend, the trend in units sold is significantly down. This suggests that price increases (+10.6% compared to the previous year) have offset the lower volume of sales.

Image 10

In New York, we found four stores with the following sales distribution:

- Tribeca at 38.3%
- Greenwich Village at 26.9%
- Harlem at 20.1%
- Brooklyn at 14.6%

We observe a less significant but very stable growth trend. However, Harlem experienced a notable drop in sales in 2015.

Image 11

Lastly, in Philadelphia, we have three stores with the following sales distribution:

- Yorktown at 36.7%
- Queen Village at 32.7%
- Midtown at 30.6%

Sales trends are stable and positive in Yorktown and Midtown. However, Queen Village shows a clearly negative trend.

Image 12.

## Items without sales in the last month.

With our refined database and after handling missing values (items with no sales), we exported a list of items not sold in the past 28 days, so the marketing or sales department can review and decide whether to remove them from stock:

'ACCESORIES_1_335', 'ACCESORIES_2_110', 'HOME_&GARDEN_1_209', 'HOME&GARDEN_1_366', 'HOME&GARDEN_2_158', 'HOME&GARDEN_2_202', 'HOME&GARDEN_2_210', 'HOME&GARDEN_2_456', 'HOME&_GARDEN_2_502', 'SUPERMARKET_1_004', 'SUPERMARKET_1_043', 'SUPERMARKET_1_120', 'SUPERMARKET_1_126', 'SUPERMARKET_2_292', 'SUPERMARKET_3_002', 'SUPERMARKET_3_008', 'SUPERMARKET_3_073', 'SUPERMARKET_3_077', 'SUPERMARKET_3_205', 'SUPERMARKET_3_210', 'SUPERMARKET_3_271', 'SUPERMARKET_3_419', 'SUPERMARKET_3_441', 'SUPERMARKET_3_444', 'SUPERMARKET_3_647'.

We will continue our Clustering and Time Series work by removing these items from our dataframe.
