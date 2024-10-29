# Clustering.
After conducting the business analysis, we will try to identify groups of products that behave similarly to more effectively focus our Marketing campaigns according to our clusters.

To do this, we will cluster by item instead of by ID, as the items show quite similar behavior across stores. We refined the database to retain the most relevant information for each item by creating new variables, such as the minimum, maximum, mean, and median of price, sales, and revenue. Similarly, these measures were also created specifically for weekends and for dates coinciding with special events.

After several iterations and tests, we ran the KMeans model to estimate up to 14 clusters, resulting in the following variation in dispersion:

Image elbow curve

After initially analyzing the results for 8 clusters, we observed that the best estimate was achieved with 4 clusters. When visually representing the behavior of price and sales, we identified groups corresponding closely to the behavior of the 4 clusters.

Thus, we created a list of items for each cluster and proceeded to analyze the segmentation in PowerBI.

We added an extra column within the clusters to flag an issue mentioned by the company, which corresponds to products with low sales. This column is labeled as 'Delete' and includes those items that we mentioned earlier for removal. Comparison of KPIs for each cluster:

|  |  Cluster 0   | Column 2   | Column 3   | Column 4   | Column 5   |
|----------|------------|------------|------------|------------|------------|
| Nº Items | 1346 | Row 1 Col 2 | Row 1 Col 3 | Row 1 Col 4 | Row 1 Col 5 |
| Mean Price | 3,78 $ | Row 2 Col 2 | Row 2 Col 3 | Row 2 Col 4 | Row 2 Col 5 |
| Items Sales | 28,25 M | Row 3 Col 2 | Row 3 Col 3 | Row 3 Col 4 | Row 3 Col 5 |
| Total Revenue | 97,53 M$ | Row 4 Col 2 | Row 4 Col 3 | Row 4 Col 4 | Row 4 Col 5 |
| Revenue per Day | 51 K$ | Row 5 Col 2 | Row 5 Col 3 | Row 5 Col 4 | Row 5 Col 5 |

