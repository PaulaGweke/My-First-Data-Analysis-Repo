# My-First-Data-Analysis-Repo - Telcom Churn Analysis

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
* Churn was 26.54% representing 1869 of the 7043 customers.
* There is high usage of paperless services by the customers; 10,752,789.65 of  16,056,168.70 payment made, representing 67% of payments.
* Automated payment made up 59% of total payments.
* Phone Services had the highest subscribers and online security had the least subscribers.
* The ratio of male to female customers is approximately same (50/50 - Chart 1/2 Summary).
* Of the payment types, Electronic Checks had the most revenue and mailed check had the least revenue (Chart 2)
* For counts (frequency of use) for payment types, Electronic Checks had the highest and Credit Checks had the least counts (Chart 1)
* Bi-Annual contract subscription gave the most revenue (39%) and Yearly contract brought the least revenue (28%). However, Most customers are subscribe to the Monthly Contract (See Chart 1).
* There are less customers with Partners (48%) than customers without Partners (52%). However, customers without partners provide 67% of the Total Revenue as shown in Chart 1.
* Customers without Dependents brought in more revenue than customers with Dependents (See Chart 1).
* Most Churn was from the Electronic Checks which had the most revenue (See Chart 2).
* Of the three Internet Services provided; DSL and Fibre Optic, it was observed that a significant amourt of customers using the Fibre Optic Internet Service left. This represents 72% of the 1799 customers subscried (see .xlsx sheet for Service Charts).
* The highest Churn is observed from the Elelctonic Checks which is used by 597 (52%) of the Seniors out of which 317 (53%) Churned (left). While Non Senior subscribed were 1771 customers, out of which approximately 43% Churned. This 52% represent 8% of the total Electronic Check revenue out of which 3.75% Churned (left). See Summurized Churn Chart gif in folder.
* More findings are displayed in Charts of Telcom_Customer_Churn_Report/Week1_Assignment_Telco_Customer_Churn.xlsx

# Recommendation
* The high Churn observed in the users of the Fibre Optic internet services suggest poor service by that service provision. This services should be analysed for it's efficiency both in technical productivity and demand due to trend. A compilation of customers' complaints and feedback on the service should be analysed for proper decision making.
* The high Churn from Electronic Checks suggest that there may be glitches in using this service that the customers prefer to use and are unhappy about the way the payment is handled. There should be proper inquiry to know the difficulties faced by customers in the use of Electronic Checks and proper solutions drawn up.
* More marketing should be target to people with partners and no dependents as they are observed to bring in more revenue.
* Bi-Annually plans should be marketed more as the plan appears to be more favoured by the Customers.

