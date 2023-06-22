# Overview
There's nothing like analyzing your own data. With over 14M views and 750K likes from my six-year content marketing career, I was motivated to start a project to examine my online presence. The results are surprising. 

# STEP #1 Extract, Transfrom and Load (ETL)
##### Data Source: 
The data source has been specified to two specific YouTube channels, with the focus of the project being only on videos I made. This is because there were a few video hosts who also published content alongside me.

##### Technology used: 
_Python, Youtube Api v3_

##### The Process: 
The data was initially a csv file containing all the URLs of my videos, Utilizing the Youtube API v3 and json libraries and data of every video has been recorded to the data frame in 2 seperate 2 csv files (1 file for each channel). Data union was performed to merge the 2 DataFrames together and loaded into MYSQL for further analysis.

# STEP #2 Exploratory Data Analysis (EDA)
My reference and guide was my favourite book in EDA which is [Practical Statistics for Data Scientists] for getting insights and to answer qustions, calculate estimates of location, find correlations, etc.

# STEP #3 Data Visualisation
This has been essential step to convert all of the data into a dashboard with interactive design.

[Link to the dashboard]
##### Tools used: 
_Microsoft Power BI_




   [Practical Statistics for Data Scientists]: <https://www.oreilly.com/library/view/practical-statistics-for/9781491952955/>
   [Link to the dashboard]: <https://app.powerbi.com/reportEmbed?reportId=aa940a2d-1651-4efd-92e2-bbed4174ce35&autoAuth=true&embeddedDemo=true>

