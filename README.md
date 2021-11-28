# PyBer_Analysis

## Overview of Project

### Purpose
A company named "V. Isualize" has asked for my assistance in analyzing some data related to specific city types and their 
related cities.  V. Isualize has provided identified the spefic data point they would like analyzed.  These metrics are 
identified below.  The standard data analysis principles were used which includes; (1) Determine the number of rows and 
columns; (2) Data types used; and (3) Is the data readable?

V. Isualize required Metrics:

- The total number of rides for each city type is retrieved.
- The total number of drivers for each city type is retrieved. 
- The sum of the fares for each city type is retrieved.
- The average fare per ride for each city type is calculated.
- The average fare per driver for each city type is calculated.
- A PyBer summary report

## Resources
City Dataset: [City Data](https://github.com/SheaButta/PyBer_Analysis/blob/main/Resources/city_data.csv)

  - Dataset analysis prior to analyzing data:
    - Opened with no issues.
    - There were three (3) columns in this dataset.
    - Each column contained a header.
    - Each column contained a city name, a driver_count and the type of city ("Urban", "Suburban", "Rural").
    - There are 120 rows.
    - There are no empty rows.

Ride Dataset: [Ride Data](https://github.com/SheaButta/PyBer_Analysis/blob/main/Resources/ride_data.csv)

  - Dataset analysis prior to analyzing data:
    - Opened with no issues.
    - There were four (4) columns in this dataset.
    - Each column contained a header.
    - Each column contained a city name, date of ride, ride fare and ride_id.
    - There are 2375 rows.
    - There are no empty rows.

## Results

The below bullets will describe the analysis results for V. Isualize. 

  - Total number of rides for each city type is retrieved.
  	- This analysis reveled that "Rural" cities consists of 125 rides; while "Surburban" and "Urban" cities sit at 625 and 1625 rides.  
  	  The "Rural" cities are behind more that three times (3x's) when it comes to total rides of all three city types.

		Total Rides Per City: 
	
		![Rides per City](https://github.com/SheaButta/PyBer_Analysis/blob/main/Resources/TotalNumOfRides_perCity.PNG)

  - Total number of drivers for each city type is retrieved.
  	- "Rural" cities only have 78 drivers while "Surburban" and "Urban" cities sit at 490 and 2,405 drivers.  Having the least number of	
	  drivers seems to reveal why "Rural" cities have he least number of rides; but, the popuplation size in these "Rural" cites could be
	  a factor as well.

  - Sum of the fares for each city type is retrieved.
  	- The first two results would seem to suggest that the "Total Fares" in "Rural" cities will be lower than "Suburban" and "Urban" cites.
	  The total fares for each city type tallied "Rural" cities at $4,327.93, "Suburban" cities at $19,356.33 and "Urban" cities
	  at #39,854.38.

  - Average fare per ride for each city type is calculated.
  	- All previous results would seem to also suggest the "Average Fares" in "Rural" cities will be lower than "Suburban" and "Urban" cites;
	  however, that's not the case.  Since the riders in "Rural" cities are not close to major cities, they may have to pay more due to the 
	  distance between their destinations.  The average fare ride in "Rural" cities is $34.62, while "Suburban" and "Urban" cities sit at 
	  $30.97 and $24.53.

  - Average fare per driver for each city type is calculated.
  	- The "Average Fare per driver" in "Rural" cities is $55.49; $39.50 in "Suburban" cities and $16.57 in "Urban" cities.  These averages
	  indicate that it's costly to ride in "Rural" areas; most likely, because of the distance between a rider's start location and destination
	  location.

  - The below visualization clearly describes the results mentioned above.

  PyBer Summary: 

  ![Rides per City](https://github.com/SheaButta/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary

This analysis for "V. Isualize" has revealed some some disparities between Rural, Suburban and Urban cities. Here are my recommendation
based on these disparities;

	1. Review the population in the "Rural" and "Suburban areas to determine if additional drivers would increase the "Total Rides" 
	   as well as the "Total Fares".

	2. Review the average salary for "Urban" areas to determine if a fare increase is possible.

	3. Review the weeks where "Rural" area fares are the least.  This may indicate holiday weeks and you may want to increase the
	   fare on specific days.


