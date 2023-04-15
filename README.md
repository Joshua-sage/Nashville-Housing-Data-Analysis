
# Analysis of Nashville Housing Data using SQL

In this project I made use of Nashville Housing Data, a dataset that contains property and land use statistics for Nashville, the state of Tennessee's capital.

This analysis' focus is on the 2013–2016 housing boom in Nashville. which should help answer the following questions:

- Which month regularly sees the highest average home sale value?
- Which month has the highest number of home sales in the year?
- what percentage of homes sold had three or more rooms
- Average sale price by year built.
- A relation between the  land use and the sale price?

## Data

This data was gotten from [GitHub](https://github.com/AlexTheAnalyst/PortfolioProjects/blob/main/Nashville%20Housing%20Data%20for%20Data%20Cleaning.xlsx), but orginally posted on [Kaggle](https://www.kaggle.com/datasets/tmthyjames/nashville-housing-data).

This dataset was imported into Microsoft SQL Management Server Studio.
## Data Cleaning

Observations from studying the dataset.
- The date is not in the standard format.
- The PropertyAddress has both the City and House Address in the same column.
- Some rows in the SoldAsVacant has Y and N instead of Yes or No.
- Some rows in the PropertyAddress is NULL
- The OwnerAddress has the state, city, and address on the same column.
- There are some duplicate rows that need to be removed.
- Useless columns should be deleted.

I began cleaning the data by spotting  and handling any missing or erroneous data, removing duplicate entries, and standardizing data formats to ensure uniformity across the dataset.

 various queries were executed in order to extract insightful information such as the most and least expensive city, the most common type of housing units sold, and the average sale price across different neighbourhoods.

I extracted and manipulated the data throughout the project using a variety of SQL commands, including SELECT, WHERE, GROUP BY, ORDER BY, and JOIN, CTEs, Temp tables, aggregate functions, and converting data types. This project helped me improve my SQL proficiency.
## Conclusion

This project demonstrates my ability to utilize SQL to clean and analyze large datasets, and provides valuable insights into the Nashville housing market.