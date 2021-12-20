# Inspect the dataset

## Scenario

As a data analyst working for an ice cream company, management is interested in improving the company's ice cream sales.

The company has been collecting data about its sales—but not a lot. The available data is from an internal data source and is based on 
sales for 2019. The request was to review the data and provide some insight into the company’s ice cream sales. Ideally, management would like 
answers to the following questions:

- What is the most popular flavor of ice cream?

- How does temperature affect sales?

- How do weekends and holidays affect sales?

- How does profitability differ for new versus returning customers?

## Dataset
https://docs.google.com/spreadsheets/d/1jJijodOT5qXzkX1hUc9nnV5uBroxHKlYNtetUUmfWq4/edit#gid=653912415

## Inspect the data

**Question 1: What is the most popular flavor of ice cream?**

To discover the most popular flavor, I first need to define what is meant by "popular." Is the most popular flavor the one that generated the 
most revenue in 2019? Or is it the flavor that had the largest number of units sold in 2019? Sometimes your measurement choices are limited by what 
data you have—you can review your spreadsheet to find out if either of these definitions of “popular” make sense based on the available data.  

The data in the excel on Falvors tab has three columns and 209 rows of data. The column headers 
are week, units sold, and flavor. This dataset did not come with a data description, so have to figure out the significance of the columns.
Based on the data, we deduce that these columns provide information about the number of units sold for each ice cream flavor, by week, in 2019.

In this case, I discovered "what the most popular flavor" by using units sold as the measure. 
In particular, I can use the units sold column to calculate the total number of units sold during the year for each flavor. Unfortunately, the dataset
does not provide the annual sales amount by flavor. In this case, the next step would be to ask the stakeholders if the annual sales per flavor data
is available from another source. If not,  add a statement about the current data’s limitations to your analysis.

**Question 2: How does temperature affect sales?**

To explore the second question, in the temperatures tab, the data may show total 2019 sales per temperature (for instance, 
the first entry might sum up $36.69 in sales for three separate days that each had a high of 60 degrees). Or, the data may show 
a snapshot of sales and temperature for each day in 2019 (for instance, the first entry might refer to a single day with a high of 
60 degrees and $39.69 in sales).

So, which is it? It’s probably a daily snapshot because there are 365 entries for temperature, and multiple rows with the same temperature and
different sales values. This implies that each entry is for a single day and not a summary of multiple days. 
However, without more information, you can’t be certain. Plus, you don’t know if the current data is listed in consecutive order 
by date or in a different order. Your next step would be to contact the owner of the dataset for clarification. 

If it turns out that temperature does affect sales, you’ll be able to offer your stakeholders an insight such as the following: 
“When daily highs are above X degrees, average ice cream sales increase by Y amount. 
So the business should plan on increasing inventory during these times to maximize sales.”

**Question 3: How do weekends and holidays affect sales?**

Next, The sales sheet has two columns and 366 rows of data. The column headers are date and sales. This data is most likely total daily
sales in 2019, as sales are recorded for each date in 2019. 


This data can be used to determine whether a specific date falls on a weekend or holiday and add a column to your sheet that reflects
this information. Then, finding out whether sales on the weekends and holidays are greater than sales on other days will be useful to know
inventory planning and marketing purposes. 

**Question 4: How does profitability differ for new customers versus returning customers?**

The dataset does not contain sales data related to new customers. Without this data, I won’t be able to answer your final question. However
, it may be the case that the company collects customer data and stores it in a different data table. 

If so, the next step would be to find out how to access the company’s customer data. I can then join the revenue sales data to the customer
data table to categorize each sale as from a new or returning customer and analyze the difference in profitability between the two sets of customers.
This information will help your stakeholders develop marketing campaigns for specific types of customers to increase brand loyalty and overall profitability. 
