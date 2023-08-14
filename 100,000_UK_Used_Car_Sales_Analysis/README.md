# UK Used Cars Sales Analysis

![My Image](https://github.com/PaulaGweke/My-First-Data-Analysis-Repo/blob/main/100%2C000_UK_Used_Car_Sales_Analysis/ttilepage.gif)


# Data Sourcing and Transformation
* The data is from Kaggle quarterly updated files on used cars in the UK. The data was downloaded from UK 100,000 used cars and the unzipped folder was imported into Power BI. 
* The file had 9,610 error rows that were identified and deleted in BI transform leaving 100800 out of 108540 rows. Additional columns were created to class mileage, engine size, tax range, car years and mpg.
* Some data cleaning such as replacing 2060 year of ford fiesta with 2006.
* Null values and empty entries were set to 0.
* Influencing factors were analysis based on the price changes with car specifications in terms of tax, age, mileage, enginesize, mpg, fuel, type, transmission type and car type.
![image](https://github.com/PaulaGweke/My-First-Data-Analysis-Repo/blob/main/100%2C000_UK_Used_Car_Sales_Analysis/car_groups.png)

# Data Findings
* 108,540 cars from 11 car types and 195 models:
* * Audi – 26 models
  * BMW – 24 models
  * CClass – 1 model
  * Focus – 1 model
  * Ford – 23 models
  * Hyundai – 16 models
  * Mercedes – 27 models
  * Skoda – 12 models
  * Toyota – 18 models
  * Vauxhall – 22 models and
  * VW – 27 models
* Card display shows that the Average price for all cars is £16,890.
* Card displays show that the oldest car was produced in 1970 (53 years) and youngest car was produced in 2020 (3 years).

![My Image](https://github.com/PaulaGweke/My-First-Data-Analysis-Repo/blob/main/100%2C000_UK_Used_Car_Sales_Analysis/UK_cars_sales1.jpg)

* Mercedes have the highest average price by car type and Vauxhall has the lowest average price as shown in bar chart. Also observed is that the highest car count is Ford (16.55%).
* Petrol has the highest count in fuel type (55%) as shown in doughnut chart, while Electric cars are only 6 in number.
* The trend of car price reduces with increase in mileage.
* The trend of price increases with decrease in car age.
* The average price by fuel type is highest in Hybrid and least in Petrol as shown in lower doughnut chart.
* Area plot of price and mileage against year shows a trend of reducing price with increased mileage and increasing price with decrease in age of car. This trend is noticeably distorted in the 1st 2000s (2000 to 2009) range.
* Top 10 most expensive car models:
 * 1 Mercedes (most expensive)
 * 4 Audis (2nd, 5th, 9th and 10th )
 * 4 BMWs (3rd, 4th, 6th, and 8th)
 * 1 VW (7th)
* The model types, transmission and fuel types can be viewed using the “Show Details” button.
* The top 10 most expensive cars are luxury brands.
* Electric cars in highlight have the low tax. 
* A new panel of charts shown in the following slides can be viewed using the “Panel 2” button.
  
![image](https://github.com/PaulaGweke/My-First-Data-Analysis-Repo/blob/main/100%2C000_UK_Used_Car_Sales_Analysis/UK_cars_sales2.jpg)

* The trend of price with mpg is hyperbolic but average price peaks around economic measure (200-300 mpg).
* Most cars (63.8%) are within the moderate tax bracket group (in this analysis - £100 - £200 ).
* Price trend increases with Engine Size with most cars having engine size between 1 and 2.
* The age range chart shows that the year most of the cars (94.6%) were made was between 2010 and 2019.
* Highest average price based on age range are Recent cars followed by Vintage cars. Cars of the 1st 2000s (2000 to 2009) have the least average price.
* Whisker plot reaffirms scatter plot trend of price decreasing with increasing mileage. The average price of cars with mileage between 100 to 999 is slightly more than that of cars with 0-99 mileage. This may be due to the presence of 1st 2000s car group range in the 10s mileage while the 100s mileage does not.
  
![image](https://github.com/PaulaGweke/My-First-Data-Analysis-Repo/blob/main/100%2C000_UK_Used_Car_Sales_Analysis/UK_cars_sales3.jpg)

* From the KPI analysis. The relationship is in line with observation. It shows price is likely to increase with:
 * Increase in mpg > 42.8
 * Greater than 6521 mileage
 * Tax between 125 and 145
 * Increase in Engine size
 * Reduction in age of car.
* More charts are displayed on the panel with the KPI results by clicking on the “More” button.
* From the ribbon charts it is observed that:
 * Most cars are with the 10000s mileage
 * Engine size is mostly between 1 and 2
 * Moderate tax range (£100 - £200) cars have the highest average price.
 * Most of the cars are manual

# Conclusion of Findings
* In conclusion, most of the cars sold are cars made between 2010 to 2019. 
* Price of cars generally increases with more recently made cars. However, vintage cars are also of moderately high price due to collections. 
* Electric cars appear to have lower tax probably due to favorable policies to encourage environmental friendly cars.
* Higher tax price appear to be associated more with luxury cars than increased mileage.
* Car prices are mostly influenced by:
 * Year of make (Cars made between 2000 and 2009 appear to be least demanded as they have the least average price and constitute cars made in age of higher carbon emission and higher fuel usage) and 
 * Mileage: Price reduces with increased mileage (due to wear and potential increase in tax).
* Due to the fact that most of the cars fall within very high gas and superbly high gas group (0 – 100 mpg) as well as manual transmission; It appears that these two factors are the most influencing factors in the sales of used cars.


