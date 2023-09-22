# Beldew-Sales-Analysis
## Project Overview 
Beldew Company is a multinational retail company that specializes in goods of all kinds including computer accessories, fashion accessories, part supplies, stationery, small appliances etc
The goal of this project is to extract key insights from the data and identify ways to improve the business operation. This dataset contains sales data to customers in Brazil.
## Data Structure
The data has the following tables:
* Customer table
* Geolocation table 
* Order items table
* Orders table
* Payments table
* Product category name translation table
* Products table
* Reviews table
* Sellers table
* Uni customer order result
## Tools used
* Microsoft PowerBI
* DAX (Data Analysis Expression) for Calculated Measures
* Power Query for transforming the Data
## Data Cleaning
Before commencing any analysis, the dataset was imported into Power Query on Microsoft Power BI for data cleaning. This serves to ensure that the data we are working with is free of errors and inaccuracies that may skew our results.
The following were checked for:
* Blank spaces and missing values.
* Proper formatting of dates.
* Proper formatting of numbers.
* Proper data type
* Duplicate data
* Null and invalid entries.
* Key columns for data integrity
## Data Modelling
After ensuring data was properly cleaned. The next step was data modelling. Here, all the tables in the dataset was linked to each other using the primary key in each table.
The tables were joined primarily through one-to-many and many-to-one relationships. However, the geolocation table was joined to the customers table by many-to-many.
## Data Analysis
For this step, I analyzed the data to key insights into it such as Total Revenue, Number of orders, number of customers, number of products, number of sellers and location of the business. This was presented in the dashboard I prepared.
I prepared a sales dashboard highlighting relevant stats such as:
* Product category with the most revenue
* Products with the highest cumulative rating
* Revenue changes with month
I also prepared a report on Customer Behaviour and Sales Performance.
## Sales Performance Report
This report was aimed at analyzing the performance of the different products and states in terms of their demand and revenue. I also looked at the changes in revenue on a monthly basis.
## Customer Analysis
I made a report on my findings on Customer Purchasing Behaviour. I prepared charts showing customer reviews, payment type, customer loyalty.
I also analyzed the distribution of payments installments among customers and number of customers per state. Lastly, I looked at Order times on a daily basis.
