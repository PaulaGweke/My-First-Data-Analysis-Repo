# John Hopkins Resource Centre Covid-19 Data Analysis Report

# Project Objectives
* The objective was to make inference and collate statistic information about the effect of the Covid-19 pandemic using data from John Hopkis Resource Centre.0
* The global records for the confirmed, death and recovery were used for this analysis.


# Data Sourcing
* File was obtained from their GitHub directory at https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series as part of the material source for 30 days data analytic learning with Excel and PowerBI

# Data Transformation - Part 1
* The data was in three parts; Confirmed, Death and Recovery record, all consisting of wide tables due to the horizontal columns of the date entry.
* The dates were unpivoted for each csv table using Power BI.
* The new long tables were merged using the Province and Country/Region columns and inner join option.
* No missing data was observed at that point.
* The Province column was remove as personal preference.
* A second table containing continents and was related to the table for global population and intercontinental analysis.
* The Second table was cleaned to match differnces in some countries namings e.g North, Korea Vs Korea North.

# Data Findings 1
* Records are from January 2020 to March 2023.
* The data records were cummulative, that is the record of the next day was the sum of previous record plus new record.
* This cause it to be difficult in getting the true sum of the records.
* Using the maximum count measure was effective with some limitations:
* * Countries with more than one provinces had more than one counting hence multiples maximum counts.
  * Inability to match the date with the measures.
* The trend could be plotted using an area chart as shown in the summarized gif (https://github.com/PaulaGweke/My-First-Data-Analysis-Repo/blob/main/CSSE_Covid_19_Data_Analysis_Report/CSSE_data_analysis_summary_report_new.gif)

# Data Transformation - Part 2
* To create a column with daily new counts instead of daily accumulative counts, the data was further cleaned using Python jupyter notebook.
* Using Script:
  * for i in range(1, len(confirmed)):
    if confirmed.loc[i, 'Lat'] != 0 and confirmed.loc[i, 'Lat'] == confirmed.loc[i - 1, 'Lat']:
        confirmed.loc[i, 'New_Confirmed'] = confirmed.loc[i, 'Confirmed'] - confirmed.loc[i - 1, 'Confirmed']
    else:
        confirmed.loc[i, 'New_Confirmed'] = confirmed.loc[i, 'Confirmed']
* This was applied to all Three files and reloaded to Power BI and transformed.
* Some error were observed in the results due to:
* * Some part of China records (from 2nd February, 2023) did not have Latitude and Longitude records and as such the script could not calculate their values.
  * Inconsistent / erroneous entry in some places where the commulative record of a subsequent date is less than the previous date.
  * Final corrections were made in excel and spurious high negatives in recovery columns were set to 0.
 
# Data Findings 2
* The final cleaned data gave a death count of 6,764,530 (representing about 1.01% of the affected population) and 672,740,690 confirmed cases (representing almost 9% of the global population).
* Recording for the Recovered cases was discontinued sometime between August and September of 2021 as shown in the attached summary picture.
* Most affected country by population percentage is Peru with 0.67% death of the total population.
* Most affected country by death count is US with about 1,123,836 deaths.
* Europe had the most confirmed cases and death counts (see summary picture). Africa had the least confirmed cases and Australia had the least death counts above Africa. No death was recorded in Antarctica.
* The Winter and Summer Olympics had not death record counts as well as three other regions (see summary).
* Two cruise ships, "Diamond Princess" and "Zaandam" were affected by the pandemic and have death records.
* The confirmed Vs Death count for both by Year and Continents was display on logarithm scales to enable visibily and for better analysis of changes.
* The death count increase from year 2020 to 2021  and dropped in 2022. Record death for this year 2023 is about 100,000 (see summary picture).
* * The death percentage of about 1% of affected global population may indicate good proactive global measures in hygiene, quarantee and medical approaches in the containing of the spread of the virus.

# Recommendation
* The records as saved in GitHub requires some Data Engineering processes for cleaning.
* Data entry should ensure consistency and accuracy to ensure best result for Data cleaning and restructuring.
* Cleaning done in this analysis result show good comparison with the sum from the measure of the maximum record for each Country / Region. It also is in comparable range with the death count from WHO records.




