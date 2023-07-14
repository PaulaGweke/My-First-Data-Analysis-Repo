# SuperStore Normalized SpreadSheet

# Project Objectives
* The project consist relationship files of a sales record for a superstore for the analysis of different key performances across the sheets. 

# Data Sourcing
* Data was imported from  https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students/blob/407c8633586a0a8901f030bd3cd34c1f0fe3cae1/Data%20Modelling%20Dataset/SuperStore_Normalized.xlsx

# Data Transformation
* The data was transformed using Power BI.
* The data was clean to correct for first row headers and any misplaced data type.
* Empty cells were removed from the dimension tables.
* A new column, 'Year' was extracted from the data.
* A new column 'Total Sales' was created from the (sales*quantiy) -(salas*quantity*discount).
* A new columm, 'COGS' was created from the difference between Total Sales and Profit.
* A new column 'Discount' was created from (salas*quantity*discount).
* The data was loaded and the realtionships between the fact and dimension sheets were established.
* Measures such as count of unique product and quatity sold were calculated.

# Data Findings
* Records span from 2014 to 2017
* 7518 total unique products are sold by the SuperStore.
* 28,405 quantities were sold
* Cost of good is 7.31 million
* Total discount is 1.15 million
* Total profit is 286,397.02
* There are four Shipment Classes;
* * First Class
  * Second Class
  * Standard
  * Same daay
* Most profit was made from Standard shipment and least profit was made from same day shipment.
* 85% of total discount is from Organic sales indicating that SuperStore is a brand of for Discount products such as Amazon or Walmart.
* More findings are displayed in Charts of https://github.com/PaulaGweke/My-First-Data-Analysis-Repo/blob/9e7db2234d6755568a1b072c9636fb918d2142dc/Data_Modelling_SuperStore_Report/SuperStore_Normalized_Data_Modelling.pbix

# Recommendation
* The profit are mostly from organic sales. The scale of the records (whether in million, billions or trillions) would determine if the sales teams should be reduced or not due to possible redundancy.
* Although the Total Discount is 15.7% of the COGS, the total sales per region is profitable.
* Least discount purchase was observed in the South Region, possibly indicating more affluent customers. Their shopping patterns should be mapped and possibly include more products according to their consumption and prompt suggestions of quality brand products.
  
