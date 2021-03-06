# Pyber_Analysis
--- 
#### Pyber requested a final analysis of key metrics and visualization of weekly fare totals grouped by type of city.  After cleaning and merging the data sets and discovering the city types, the number of rides was totaled as well as the sum of drivers and fares by city type.  Then calculations using those values returned the average fares per ride and per driver by city type.  Ultimately, the weekly fare totals were graphically presented (see Image 1).  These two analyses showed that the highest total revenue is seen in urban communities, as expected based on the total volume of rides.  The more densely populated centers had greater utilization of the service.  However, the highest revenue per ride is seen in rural settings.  The rural distances could likely be the determining factor, but with the given data set, it is an assumption.  Including ride start/stop times and distance in the data sets will easily answer this next question.
---
![SummaryDF](https://github.com/TrentBrunson/PyBer_Analysis/blob/master/analysis/SummaryDF.png)
###### Table 1.  Revenue summary by city type.
![TotalFarebyCityType](https://github.com/TrentBrunson/PyBer_Analysis/blob/master/analysis/Challenge_Chart.png)
###### Image 1.  Total fare by City Type
---
#### The technical difficulties were not particularly difficult or unique.  The most challenging aspect was the blocker for the next level of analysis.  Are these key metrics being used to drive a behavior?  Is a priority shift needed?  Is it topline or bottom-line?  What are the concerns (e.g. operational efficiency, etc.)?  The request was for two simple, specific tasks; however, without communication of intent and purpose, the analytics performed were delivered exactly as requested.  Other tools exist to transform data into information to answer those other questions.  Without understanding of a larger vision, the analysis remains constrained.
---
#### For future consideration, recommend double-clicking into fares by city type by aggregating two more data elements.  Ride data includes length of ride, both distance and time (it was excluded from this data set).  Analysis of fare per unit distance and fare as a function of time would inform efficiency measures and potentially reveal opportunities to improve the bottom-line.  Technically, these two metrics are as easy to calculate as fare by city type -- they would use the same methods.  Lastly, if there is data to correlate customer information to rides, a frequency and customer retention analysis could commence which will help drive topline growth.  Grouping ride ID by customer (can be an arbitrary customer ID for data privacy regulations) will show who uses the service the most.  Then correlating this with city type can inform marketing strategies (answer the question: Where do I use limited marketing dollars?) and minimize cost of customer acquisition.
---


