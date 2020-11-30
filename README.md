# GA-Election-Data-2020
Collection of datasets and analysis from Georgia's 2020 General Election Results

## Repository File Contents
**GA_GenElecRes2020_precinct_wACS.geojson**

GeoJSON file of Georgia's 2020 general election voting precints (n=2683). Geospatial boundaries are as defined in this publicly available statewide precinct shapefile: 

*Voting and Election Science Team, 2020, "2020 Precinct Shapefiles", https://doi.org/10.7910/DVN/XPW7T7, Harvard Dataverse, V5*

It also contains precinct-level election results from the 2020 general election for the presidential and senate races, expressed in terms of total votes for each candidate broken down by voting method (e.g. election day, absentee by mail etc.)

Additionally, there are 31 precinct-level socioeconomic variables derived from the 2014-2018 American Community Survey (ACS) at the census block group level (n=5528), obtained from [NHGIS](https://www.nhgis.org/). Using 2018 TIGER/Line+ Georgia block group boundaries, area-weighted-average values of these block-group ACS variables were calculated within each precinct boundary. 

**NOTE:** These ACS values do NOT represent the exact characteristics of 2020 election voters, but rather estimated charcteristics of residents living within precincts according to the 2014-2018 ACS.


**metadata.csv**

Descriptions of all attribute fields found in the precinct geojson file.

