# IDNYC Data Analysis Project

Approximately 2.2 million IDNYC cards have been issued since 2015. 



Using data from NYC OpenData, we can graph the number of IDNYC cards issued each year. Each row in our dataset contains the number of cards issued each month, so we can downsample our data to a yearly basis, and then plot it. 



After an initial spike, the number of cards issued each year stabilize to between one hundred thousand and two hundred thousand. 



Do you think the pattern will continue? 




![image](Assets/IDNYC_Post-Assets/Cards_Issued_Graph.png)



About the chart:



The number of cards issued for the year 2024 is left off the chart because the year is not over yet, and the number would look artificially low.



About the data:



During the year 2023, there is no row for the month of November, so it is not clear whether no cards were issued that month, or that the number of cards issued was not reported for that month. I'm leaning towards the number not being reported, but I'm not sure. December has a spike that is 33% greater than the month of October, but I don't think this gives any information on the missing month.

If we take the midpoint of the cards issued for October and December,  and add it on to the value for 2023, we would go from around 160,000 to around 180,000 cards issued. Either way, this value does not differ too much from the adjacent years.

![image](Assets/IDNYC_Post-Assets/Missing_November_Graph.png)


The red dot represents the midpoint estimate for the number of cards issued in November 2023. This estimate was not used when plotting the yearly totals of cards issued.



The source for this data can be found on:



https://data.cityofnewyork.us/Social-Services/IDNYC-Applications-and-Cards-Issued/rtmc-bhid/about_data
