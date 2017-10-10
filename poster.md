EDA of H1B Applications
========================================================
author: Sumedh R. Sankhe
date: 10/09/2017
autosize: true

Background
========================================================

The Bureau of Labor Statistics Provides year data on H1B visa applications, the data used in this presentation was downloaded from the following link during the Spring of 2017 and used for project for the course DA-5020 Collecting Storing and Retreiving Data. The Data contains visa application responses from 2013 to Q1-2017. As of 9th September 2017 the link is non-functional.   

https://www.foreignlaborcert.doleta.gov/performancedata.cfm#dis


- The Data Was Cleaned
- Broken down into a SQL-Lite database
- The Database Queried using dplyr and plotted using ggplot2



Most H1B Applications for an Employer
==========================================================

|Company                             | Freq|
|:-----------------------------------|----:|
|MICROSOFT CORPORATION               |  179|
|FACEBOOK INC                        |  107|
|UBER TECHNOLOGIES INC               |   54|
|TWITTER INC                         |   32|
|AIRBNB INC                          |   25|
|GROUPON INC                         |   20|
|LINKEDIN CORPORATION                |   20|
|IBM CORPORATION                     |   19|
|AGILONE INC                         |   18|
|WALMART ASSOCIATES INC              |   18|
|SCHLUMBERGER TECHNOLOGY CORPORATION |   15|
|INTUIT INC                          |   14|
|INTEL CORPORATION                   |   13|
|LYFT INC                            |   13|
|PAYPAL INC                          |   13|
***
Thus we see that Microsoft, Facebook and Uber are leading the charts for number of H1B visa applications for Data Scientists from the year 2013 to the first quarter of 2017  

Pay Variations of a Data Scientist by State
========================================================
Probably having a co-op or an internship somewhere in California, New York, New Jersey, Washington or Massachusetts could be rewarding.
![plot of chunk unnamed-chunk-2](poster-figure/unnamed-chunk-2-1.png)




