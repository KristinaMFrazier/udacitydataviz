# Exploration of Etsy Listing Data for Artificial Crepe Paper Flower Products
## by Kristina Frazier


## Dataset

This project uses data that I extracted and cleaned from the Etsy.com API. Specifically, I extracted listings for artificial crepe paper flower products from Etsy.com in July 2020 in order to learn more about the artificial crepe paper flower market.

I extracted and cleaned this data myself using SQL and Python. Cleaning the data included dropping extraneous columns from the main listing data table, and creating a more tidy dataset by breaking out some columns into separate tables. These columns included multiple observations (essentially "lists within lists"), and were represented in separate tables. This project included some additional cleaning steps such as revising one column to be an ordered categorical data type, and the convert another column into all lower case for ease of grouping data.


## Summary of Findings

 - Based on the strong right skew of number of favorers and views, this data may have recency bias towards newer listings
 - The price data is heavily skewed to the right, necessitating analyzying the data for products only within the range of products up to $200.
 - Most listings use 1 to 3 tags, and the mostly commonly used single tag is "crepe paper." (Tags are used to enhance search results for buyers.)
 - The majority of crepe paper flower product listings are made to order.
 - Made to order products are on average higher priced than premade products.
 - Crepe paper flower product listings that are marketing towards weddings, whether made to order or premade, are higher priced than those that are not.


## Key Insights for Presentation

1. The median price of crepe paper flower products is about 20.00 USD
2. Wedding products are on average priced higher than non-wedding products
3. Made-to-order wedding products have the highest median price.
