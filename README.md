# Analyzing Turnout in Boston's Municipal Elections

## Project Description
My team in [DPI-663](https://innovategovernment.org/), a Harvard Kennedy School class on Technology and Innovation in Government, worked with the City of Boston’s Elections Commission and the Department of Innovation and Technology to tackle low voter-turnout in Boston's municipal elections. Our goal was to develop policy recommendations and product prototypes that Boston can implement to improve turnout in future municipal elections. In order to better understand the problem, I dug into some data! 

You can see the final write-up of my analysis [here](https://rpubs.com/dashamet/boston-elections). 

To learn more about the project, check out our blogs and final presentation [here](https://innovategovernment.org/boston-elections-2020). 

## Code

* `Analysis.Rmd` contains the code and write-up for the analysis. It produces the HTML file `Analysis.html`.

## Data

* `precincts.geojson` is a geospatial dataset of the City of Boston's voting precincts. I obtained this data from [Analyze Boston](https://data.boston.gov/dataset/precincts). 

* `wards.geojson` is a geospatial dataset of the City of Boston's voting wards. I obtained this data from [Analyze Boston](https://data.boston.gov/dataset/wards). 

* `dem_data_by_precincts.xlsx` is a dataset containing demographic data on Boston's precincts. I requested this dataset from Boston's Planning and Development Agency (BPDA). 

* `elections_data.xlsx` is a dataset containing the number of residents, registered voters, votes cast, and voter turnout for Boston's precincts in municipal elections from November 2005 to November 2017 (excluding special municipal elections and preliminary municipal elections). I created this dataset using the [election data](https://www.boston.gov/departments/elections/state-and-city-election-results) available on the City of Boston website. 

