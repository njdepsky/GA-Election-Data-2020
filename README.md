# GA-Election-Data-2020
Collection of datasets and analysis from Georgia's 2020 General Election

## Contents (/data folder)
**GA_GenElecRes2020_precinct_wACS** <br/>
Available both as a CSV (no spatial geometry) and as a spatial GeoJSON file (stored in .zip file) of Georgia's 2020 general election voting precints (n=2683). Boundary geometries represented in the GeoJSON were obtained from: 

*Voting and Election Science Team, 2020, "2020 Precinct Shapefiles", https://doi.org/10.7910/DVN/XPW7T7, Harvard Dataverse, V5*

It also contains precinct-level election results from the 2020 general election for the presidential and senate races, expressed in terms of total votes for each candidate broken down by voting method. These results were obtained from the [Georgia Secretary of State Webpage](https://results.enr.clarityelections.com/GA/105369/web.264614/#/access-to-races)

There are also 31 socioeconomic variables derived from the 2014-2018 American Community Survey (ACS) obtained from [NHGIS](https://www.nhgis.org/). Using 2018 TIGER/Line+ Georgia block group boundaries (n=5528), area-weighted-average values block group level ACS variables were calculated for each precinct boundary. 

**NOTE:** These ACS values do NOT represent the exact characteristics of 2020 election voters, but rather estimated charcteristics of residents living within precincts according to the 2014-2018 ACS. <br/><br/>

**metadata.csv** <br/>
Descriptions of all attribute fields found in GA_GenElecRes2020_precinct_wACS.geojson <br/><br/>

## Election Results Examples
<img src="./img/GA_GE2020_BidenOssoffPct.jpg" width="800" height = "400">

<img src="./img/GA_GE2020_SpecialSenatePct.jpg" width="800" height = "400"> <br/><br/>
