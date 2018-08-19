## Select the Location of a New Pet Store

A pet store chain is selecting the location for its next store.

Use data preparation techniques to build a robust analytic dataset and use it to build a predictive model to select the best location.

### Business Problem
Pawdacity is a leading pet store chain in Wyoming with 13 stores throughout the state. This year, Pawdacity would like to expand and open a 14th store. Your manager has asked you to perform an analysis to recommend the city for Pawdacity’s newest store, based on predicted yearly sales.

Your first step in predicting yearly sales is to first format and blend together data from different datasets and deal with outliers.

Then, you will take this dataset that you cleaned up and use this dataset to train a linear regression model in order to predict sales.

Here are the criteria given to you in choosing the right city:

1. The new store should be located in a new city. That means there should be no existing stores in the new city.
2. The total sales for the entire competition in the new city should be less than $500,000
3. The new city where you want to build your new store must have a population over 4,000 people (based upon the 2014 US Census estimate).
4. The predicted yearly sales must be over $200,000.
5. The city chosen has the highest predicted sales from the predicted set.

Your manager has given you the following information to work with:

- The monthly sales data for all of the Pawdacity stores for the year 2010.
- NAICS data on the most current sales of all competitor stores where total sales is equal to 12 months of sales.
- A partially parsed data file that can be used for population numbers.
- Demographic data (Households with individuals under 18, Land Area, Population Density, and Total Families) for each city and county in the state of Wyoming.

### Data
- competitor-sales.csv - Competitor sales
- demographic.csv - Demographic data
- population.csv - Population data
- pawdacity-monthly-sales.csv - Pawdacity monthly sales

### Tasks
- Recommend the city for Pawdacity’s newest store, based on predicted yearly sales.

### Results and Recommendation
<a href="https://github.com/ayumiohashi/udacity-business-analyst/blob/master/02-select-location-of-a-new-pet-store/reports/data-cleanup.pdf">2.1 Data Cleanup</a>

<a href="https://github.com/ayumiohashi/udacity-business-analyst/blob/master/02-select-location-of-a-new-pet-store/reports/recommendation.pdf">2.2 Recommendation</a>
