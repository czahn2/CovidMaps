# CovidMaps
# Camille Zahn

This project aims to visualize Covid-19 case rates across United States counties. One map is a choropleth map and the other uses proportional symbols to visualize the data. 

In order to create these maps, I used Mapbox API. The COVID-19 case/death data I used is originally from The [New York Times](https://github.com/nytimes/covid-19-data/blob/43d32dde2f87bd4dafbb7d23f5d9e878124018b8/live/us-counties.csv). The data include all the cases in 2020. The population data used for calculating the case rates are from the [2018 ACS 5 year estimates](https://data.census.gov/cedsci/table?g=0100000US.050000&d=ACS%205-Year%20Estimates%20Data%20Profiles&tid=ACSDP5Y2018.DP05&hidePreview=true). Both data are at the county level. The U.S. county boundary shapefile was downloaded from the [U.S. Census Bureau](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html).

## Maps
[Map 1 - Choropleth](http://127.0.0.1:5500/CovidMaps/map1.html)
![Map1](/CovidMaps/img/Map1_ZAHN.png)

[Map 2 - Proportional Symbol](http://127.0.0.1:5500/CovidMaps/map2.html)
![Map2](/CovidMaps/img/Map2_ZAHN.png)


I used the map.on function in Javascript to load the map and provide functionality on click. 

## Acknowledgement

The data for this lab was processed by Steven Bao, and detailed instructions were provided by Bo Zhao. I also recieved assistance from the course TA, Liz Peng.