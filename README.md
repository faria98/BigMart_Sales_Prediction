# BigMart_Sales_Prediction

The data scientists at BigMart have collected sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store.

Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

## Hypothesis Generation
This is a very important stage in any machine learning process. It basically involves brainstorming and coming up with as many ideas as possible about what could affect the target variable. It helps us in exploring the data at hand more efficiently and effectively. Hypothesis Generation should be done before seeing the data or else we will end up with biased hypotheses. Following are some of the hypotheses based on the problem statement.

- Sales are higher during weekends.
- Higher sales during morning and late evening.
- Higher sales during end of the year.
- Store size affects the sales.
- Location of the store affects the sales.
- Items with more shelf space sell more.

## The Data
We have train (8523) and test (5681) data set, train data set has both input and output variable(s). You need to predict the sales for test data set.

Variable | Description
----------|--------------
Item_Identifier | Unique product ID
Item_Weight | Weight of product
Item_Fat_Content | Whether the product is low fat or not
Item_Visibility | The % of total display area of all products in a    store allocated to the particular product
Item_Type | The category to which the product belongs
Item_MRP | Maximum Retail Price (list price) of the product
Outlet_Identifier | Unique store ID
Outlet_Establishment_Year | The year in which store was established
Outlet_Size | The size of the store in terms of ground area covered
Outlet_Location_Type | The type of city in which the store is located
Outlet_Type | Whether the outlet is just a grocery store or some sort of supermarket
Item_Outlet_Sales | Sales of the product in the particulat store. This is the outcome variable to be predicted.

## Dataset
Link - https://www.kaggle.com/devashish0507/big-mart-sales-prediction
