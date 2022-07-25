<<<<<<< HEAD
# Surf's Up Challenge
## Module 9: Surf's Up with Advanced Data Storage and Retrieval

## Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis is to gather more information about temperature trends before opening the surf shop in Oahu. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

### Resources: 
Data Source:  SurfsUp_Challenge.ipynb, hawaii.sqlite
Software/Programs: Python, Pandas functions and methods, SQLalchemy, Jupyter Notebook

This assignment consists of two technical analysis deliverables and a written report. You will submit the following:

### Deliverable 1: Determine the Summary Statistics for June
- Using Python, Pandas functions and methods, and SQLAlchemy, filter the date column of the Measurements table in the hawaii.sqlite database and write a query to retrieve all the temperatures for the month of June. 
- The temperatures are added to a list.
- The list of temperatures is converted to a Pandas DataFrame.
- Generate the summary statistics for the dataframe for the month of June.

![June_Results](https://github.com/veenapu/surfs_up/blob/main/June%20Results.PNG)

![June_Summary_Statistics](https://github.com/veenapu/surfs_up/blob/main/June%20Summary%20Statistics.PNG)

![Junes_results_DataFrame](https://github.com/veenapu/surfs_up/blob/main/June%20results%20DataFrame.PNG)


### Deliverable 2: Determine the Summary Statistics for December
- Using Python, Pandas functions and methods, and SQLAlchemy, filter the date column of the Measurements table in the hawaii.sqlite database and write a query to retrieve all the temperatures for the month of December. 
- The temperatures are added to a list.
- The list of temperatures is converted to a Pandas DataFrame.
- Generate the summary statistics for the dataframe for the month of June.

![December_Results](https://github.com/veenapu/surfs_up/blob/main/December%20Results.PNG)

![December_Summary_Statistics](https://github.com/veenapu/surfs_up/blob/main/December%20Summary%20Statistics.PNG)

![December_results_DataFrame](https://github.com/veenapu/surfs_up/blob/main/December%20results%20DataFrame.PNG)


### Deliverable 3: A written report for the statistical analysis (README.md)
-  A high-level summary of the results and two additional queries included in the README that would perform to gather more weather data for June and December.

Even though temperatures varu in Oahu, the average temperatures only vary by 4 degrees.  Hence, Oahu is ideal for surfing and consuming ice cream consumption, hence a surf and ice cream shop business can be set up.

In order for this business to be successful, addition queries that can be run to strengthen this further is:
1. Summary statistics for each month by station can be run, which helps narrow down, where in Oahu, is the best location to set up shop.

2. Other factors can be examines such as wind conditions, wave patterns, location with heavy foot traffic, precipitation. 









