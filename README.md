# Project 7 - Digging into the DEA Opiate Database
## Group 1

##Goal
The goal of our project was to try and find correlations between opiate usage and socioeconomic characteristics.


##Hypothesis
Counties with lower incomes and counties whose residents work construction jobs will typically correlate with higher opiate distribution rates.


##Data
Our main data source a DEA database that tracks the path of every prescription opiate pill distributed from the manufacturer to the the pharmacies where they reach the end user. The database was published by the [Washington Post](https://www.washingtonpost.com/investigations/76-billion-opioid-pills-newly-released-federal-data-unmasks-the-epidemic/2019/07/16/5f29fd62-a73e-11e9-86dd-d7f0e60391e9_story.html) and contained over 80gb of raw data.

The socioeconmic data was pulled from the US Census API.

The cleaning and parsing the DEA data was a difficult task given it's size. We used programs outside of Python as well as Linux commands to get the data into readable and useable objects. Becuase of the size we narrowed our analysis down to the County level in the state of Texas.

The 'Census Data Wrangling and Cleaning' notebook was used to clean, filter and export into csv the census data that we used.


##Analysis
The analysis was done in two separate notebooks. The 'Pill Quantity Correlations" notebook was used to look for any correlation that existed between the county level pill quantities and the census data that we pulled.

The 'Texas Analysis' notebook was used for our chloropleth visulaizaitons.

##Conclusions and Next Steps
There were no clear or statistically significant correlations in the observed census data to opiate distribution.

Contrary to our hypothesis, construction jobs have a negative correlation to opiate distribution while STEM jobs have a positive correlation.

Next steps would be to evaluate opiate related overdoses and deaths and work to correlate to distribution numbers and population to try and find where opiates are being appropriately prescribed rather than abused.

