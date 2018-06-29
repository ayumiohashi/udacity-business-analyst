## Grocery Store Formats And Inventory Planning
A grocery store chain is planning a significant expansion.

Use multiple analytical techniques to provide recommendations on how to expand.

### Business Problem
Your company currently has 85 grocery stores and is planning to open 10 new stores at the beginning of the year. Currently, all stores use the same store format for selling their products. Up until now, the company has treated all stores similarly, shipping the same amount of product to each store. This is beginning to cause problems as stores are suffering from product surpluses in some product categories and shortages in others. You've been asked to provide analytical support to make decisions about store formats and inventory planning.

### Task 1: Determining Store Format for Existing Stores
To remedy the product surplus and shortages, the company wants to introduce different store formats. Each store format will have a different product selection in order to better match local demand. The actual building sizes will not change, just the product selection and internal layouts.

- Determine the optimal number of store formats based on sales data.
- Sum sales data by StoreID and Year
- Use percentage sales per category per store for clustering (category sales as a percentage of total store sales).
- Use only 2015 sales data.
- Use a K-means clustering model.
- Segment the 85 current stores into the different store formats.

##### Data
- store-sales-data.csv - store sales
- store-information.csv - store information

### Task 2: Determine the Store Format for New Stores
- Develop a model that predicts which segment a store falls into based on the demographic and socioeconomic characteristics of the population that resides in the area around each new store.
- Use a 20% validation sample with Random Seed = 3 when creating samples with which to compare the accuracy of the models. Make sure to compare a decision tree, forest, and boosted model.
- Use the model to predict the best store format for each of the 10 new stores.

##### Data
- store-demographic-data.csv -  information for the area around each store

### Task 3: Forecasting Produce Sales
- Provide a monthly forecast for produce sales for the full year of 2016 for both existing and new stores.
