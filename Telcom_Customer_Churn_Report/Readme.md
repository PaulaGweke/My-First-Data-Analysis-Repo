# Telcom Churn Analysis

# Project Objectives
* The project consist of the customer quarterly report on the record of a telicommunication company offering eight (services):
  * Phone Services
  * MultipleLines Services
  * InternetServices
  * OnlineSecurity Services
  * Online Backup Services
  * DeviceProtection Services
  * Technical Support Services
  * Streaming TV Services and
  * Streaming Movies Services
* The aim of the analyse the Churn (loss) of customers over the past month and to establish a relationship as to possible causes and recommend solutions.

# Data Sourcing
* Data was imported from https://kaggle.com/datasets/blastchar/telco-customer-churn/download?datasetVersionNumber=1

# Data Transformation
* The data does was transformed using Excel. The column for senior citizens stored in boolean (0, 1) format was replaced with values of <65 years for 0 and > 65 years for 1.
* The response on the services provision for 'No internet Service' was abbreviated to 'No internet'
* An additional colomn called 'Automated Payment) was extracted from types of payment using a delimiter of '('.
* Bank and Credit cards payment made up the automated payment.
* The Contract column content was renamed for better presentation.

# Data Findings
* There are 7043 customers subscribed to the Telcom offering eight (8) services across three (3) payment plans (monthly, yearly, Bi-Anually).
* There are 1142 (16%) Senior and 5901 (84%) Non Senior customers. The Senior customer are 65 years and above.
* Churn was 26.54% representing 1869 of the 7043 customers representing 41.6% of the senoir customers and 23.6% of the Non Senior customers.
* The churn percentage is  and 18% ( 2,862,926.90 of 16,056,168.70) of Total Charges
  
 ![My Image](https://github.com/PaulaGweke/My-First-Data-Analysis-Repo/blob/main/Telcom_Customer_Churn_Report/Telco_Customer_Chart1_new.gif)
  
* There is high usage of paperless services by the customers; 10,752,789.65 of  16,056,168.70 payment (Total Charges) made, representing 67% of payments.
* Automated payment made up 59% of total payments.
* Phone Services had the highest subscribers and online security had the least subscribers.
* Movie streaming services lost 
* The ratio of male to female customers is approximately same (50/50 - Chart 1/2 Summary).
* Of the payment types, Electronic Checks had the most revenue and mailed check had the least revenue (Chart 2)
* For counts (frequency of use) for payment types, Electronic Checks had the highest and Credit Checks had the least counts (Chart 1). It also generated the highest payment types in Total Charges, representing 30.8 percent of the Total Charges.
* Bi-Annual contract subscription gave the most revenue (39%) and Yearly contract brought the least revenue (28%). However, Most customers (3875 representing 55% of the customers) are subscribe to the Monthly Contract (See Chart 1).
* There are less customers with Partners (48%) than customers without Partners (52%). Customers with partners had more tenures and contributed to 64% of the revenue / Total Charges.
  
 ![My Image](https://github.com/PaulaGweke/My-First-Data-Analysis-Repo/blob/main/Telcom_Customer_Churn_Report/Telco_Customer_Chart2_new.gif)
 
* 70% of the customers (4933) did not have dependents and brougt in 67% of the total Charges (Seet Chart 1).
* Most Churn was from the Electronic Checks which had the most revenue amd most of them are subscribed to the monthly payment plan (See Chart 2).
* Of the three Internet Services provided; DSL and Fibre Optic, it was observed that a significant amourt of customers using the Fibre Optic Internet Service left. This represents 72% of the 1799 customers subscried (see .xlsx sheet for Service Charts).
* The highest Churn is observed from the Elelctonic Checks which is used by 597 (52%) of the Seniors out of which 317 (53%) Churned (left). While Non Senior subscribed were 1771 customers, out of which approximately 43% Churned. The 52% of seniors using electronic checks represent 10.6% of Total Charges and 3.75% Churned (left). See Summurized Churn Chart gif in folder.

  [!My Image](https://github.com/PaulaGweke/My-First-Data-Analysis-Repo/blob/main/Telcom_Customer_Churn_Report/Churn_Summary_Chart.gif)
    
* More findings are displayed in Charts of https://github.com/PaulaGweke/My-First-Data-Analysis-Repo/blob/87179aed79696cb6590bae5930a3e91c28d3d458/Telcom_Customer_Churn_Report/Week1_Assignment_Telco_Customer_Churn.xlsx

# Recommendation
* The high Churn observed in the users of the Fibre Optic internet services suggest poor service by that service provision. This services should be analysed for it's efficiency both in technical productivity and demand due to trend. A compilation of customers' complaints and feedback on the service should be analysed for proper decision making.
* The high Churn from Electronic Checks suggest that there may be glitches in using this service that the customers prefer to use and are unhappy about the way the payment is handled. There should be proper inquiry to know the difficulties faced by customers in the use of Electronic Checks and proper solutions drawn up.
* More marketing and appealing offers should be developed towards retaining Monthly subscribers.
* More marketing should be target to people with partners and no dependents as they are observed to bring in more revenue.
* Bi-Annually plans should be marketed more as the plan appears to be more favoured by the Customers.


