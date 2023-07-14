# Best and Worst States to Retire in US Analysis

# Project Objectives
* The project consist of analysis of 50 States in the USA for best place to retire base on 5 measurements;
  * Affordability (This makes up 40% of the Overall Score)
  * Wellness (This makes up 20% of the Overall Score)
  * Culture and Diversity (This makes up 15% of the Overall Score)
  * Weather (This makes up 15% of the Overall Score)
  * Crime (This makes up 10% of the Overall Score)
* Using the Overall Score, the States were ranked from 1-50. 1 representing best indices and 50 represnting Worst indices. For Crime, 1 represents least crime rate and 50 represents highest crime rate.

# Data Sourcing
* Data was imported from  https://www.bankrate.com/retirement/best-and-worst-states-for-retirement/

# Data Transformation
* The data was transformed using Power BI.
* There were no empty cells so no data was removed, howeever, the data required some cleaning for some column types corrections.
* A new column was created called 'Total Score' to affirm the Overall Score based on the ratio quoted as used.
* The data was duplicated to create another table ...Transform, where the 'Inverse Score' (50 for the best and 1 for the worst) of the measure was computed and the Measures pivoted to plot the chart for the indices of certain states of interest and for aesthetic displays.

# Data Findings
* Florida has the best Ranking as shown in the Charts and Alaska has the Worst Ranking (see Chart 1).
* Based on the five (5) measures, the best Ranking State in each measurement are:
  * Affordabitity - Michighan
  * Well-ness - Massachusetts
  * Culture and Diversity - Florida
  * Weather - Arizona
  * Crime - New Hampshire
* The top 5 ranking states from the Overall Score ranking differ slightly from the recalculation of the indeces in the Total Score top 5 States (See Chart 1 and Chart 3 gifs).
* Hawaii had good indices but fell out of the Top 5 ranking due to high cost (ranked as the most expensive state, #50).
* Also Kentucky had good indices but measured worst in Culture and Diversity
* New Jersey also has good measurement of low Crime, great Well-ness, good Cultural Diversity and moderate Weather but high cost in Affordability.
* Alaska has a surprising record as second worst (49) in Crime.
* Some measurements were the ranking between states were the same were similar. These values were not altered in this analysis as they represent relative measurements.
* More findings are displayed in Charts of Best_Worst_States_To_Retire_In_US_Project/Best_Worst_US_States_to_Retire.pbix

# Recommendation
* The ranking with only 10% for crime should be revised as the Crime rate in an area could also indicate the level of serenity in a place. Also most retirees are senior citizens who are more vulnerable. The rate should be increased to at least 20%.
  * A measurement using 35% Affordability, 20% Crime, 15% Well-ness, 15% Culture and Diversity and 10% Weather is shown in ...Transform 2 'Total Score 2' display on panel 3 of the Power BI sheet in the folder.
* The sheet can be made dynamic with customer option to regulate their top choices based on their ranking of the 5 measurements along with some guidance. 
* Hawaii is a good retirement state for high income / rich retirees and people who prefer low Cultural diversity have great indices in states like Kentucky and West Viginia,
