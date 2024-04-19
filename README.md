# BuildingAI
project for BuildingAI

# Project Title
Monitoring the energy efficiency of buildings

## Summary
Monitoring the energy efficiency of buildings - the tool will help building owners better manage energy consumption

## Background
Buildings generally consume 30% of energy and produce 25% of CO2 emissions. In most older buildings, the savings potential is 20-35%. In some buildings that have an undetected error in their process, the savings potential is even greater.

## How is it used?
The program would be used by building owners and building maintenance to detect abnormalities in buildings.

## Data sources and AI methods
There is currently no universal open data on energy consumption for buildings. In the future, there could be an open data source with data from public building owners such as municipalities. For now, all building owners would have to use their own energy consumption data. For larger municipalities, it is hundreds to thousands of buildings and that could be enough for a reliable model. Energy companies also have large stores of data. Main energy meters of buildings are mostly used on the basis of invoicing. Other suitable data are weather data from the National Weather Service and building data.
I would use linear regression where the variables are things like outside temperature (hourly data), wind speed (hourly data) and solar radiation (hourly data) from a weather dataset. Other necessary variables are building size (area or volume), indoor temperature, year of construction and number of users. The assumed values would be the consumption of heat and electricity. The program would compare the predicted value with the actual value and report any deviations. The program also compares different building coefficient values with each other and estimates buildings that have abnormal values. If the program had access to the building management system, even more variables could be used.

## Challenges
The program does not fix real bugs that would need to be done manually. It can also be very difficult to correctly estimate the exact error without very detailed monitoring in the building, and getting data from the building management system into the AI program can be challenging. An early build of the program could produce a list of errors that fit the characteristics of the data.

## What next?
The next step of the program could be to influence the design of future buildings from the learned data of existing buildings. The program could analyze existing buildings to determine what works and what doesn't, and give guidance to designers of new buildings.

## Acknowledgments
https://www.scdi.tech/ 
