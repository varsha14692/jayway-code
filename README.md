# Estore sales predict:

Predict the estore sales using the Python Pandas library.

# Questions for missing data:

1. Should we remove all the missing data from dataframe?
2. Or should we convert the missing values as a fixed value?
3. Since, Quanity column contains missing values, should we take an average of quanity and predict the sales?

# Background Information:

I have used Python Pandas to analyze and answer business questions about the given ecommerce sales data. The data contains InvoiceDate, InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country, Estore_id.

Below steps were performed inorder to predict the overall sales by each estore in every country. Based on the prediction, client may dis-continue less profitable estores. 

1. Data Cleansing.  
  -> Removed duplicate data.  
  -> Based on answer of question 3, mising quantity can be managed. For now, we have removed the rows which has missing quantity.  
2. Take the average of the total sales for each estore in each country.  
3. Sort the data based on average sales.
4. Based on the final resultset, client can predict the overall sales.
