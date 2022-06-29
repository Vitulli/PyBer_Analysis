# Overview of PyBer Ride Analysis
### PyBer Management asked for a breakdown, via Jupyter Notebooks, of their income streams based on demographics.  The demographic breakdown was across area types described as Rural, Suburban, and Urban.  Other analyses were conducted prior to this final study, and it was agreed that this summary analysis was key to the decision makers.

# Results of Final Study Cumulative Fares Vs. City Type
### Two data sets were joined to create the final dataframe for this analysis.  These were city_data.csv and ride_data.csv.  City data contained the name of the city, the number of drivers for that city, and the demographic of that city (Rural, Suburban, Urban).  Ride data contains details about every ride’s details of the city, date and timestamp of the fare, the fare amount, and the unique ride id.  These two data sets were merged to yield the results listed here.

### Other analysis was conducted, and these will be presented as well to aid in the overall summary.
# Summary, Recommendations, and Graph Detailing Results

## Total Number of Rides per Day (per Type) Vs. Average Fare
![](analysis/Fig1.png)
### As it can be seen the number of daily rides are given in an Urban environment as would be expected but due to the short nature of ride the average fare tends to be lower than the other demographics.  We will couple this idea to the summary later.

##Total Fare by City Type Vs Weekly Average Summed Fares
![](TotalFareCityType.png)

With these two graphs a comprehensive picture emerges.
1.	Though collected average fares in the Urban areas of the city tend to be smaller they constitute the bulk of the company’s revenue and emphasis should on creating a greater market share.
2.	Suburban areas show promise as the collected fares tend to be greater than any of the Urban fares and represent a medium between the Urban and Rural leadership may want to see if additional efforts in this area are fruitful.
3.	Rural areas, while constituting the largest average fare due to the milage incurred, constitutes very little of PyBer’s monthly revenue.
