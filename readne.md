## Web map link

URL: https://[your_github_username].github.io/[your_repository_name]/

## What this project is

A smart dashboard web map showing SNAP retailer locations in Seattle and per-capita income by census tract. Food access (SNAP retailers) compared with neighborhood income patterns in Seattle, WA.

## Map type and why

Choropleth because income is an area-based value and census tracts are the best way to compare neighborhoods. It also makes it easy to spot clusters of higher and lower income areas at a glance while you compare them with nearby SNAP locations.

## Dashboard components

Dynamic numbers for total retailers and retailers in view
Chart showing retailers by income level (updates with the map view)


Data Sets:

SNAP Retailer CSV - https://usda-snap-retailers-usda-fns.hub.arcgis.com/datasets/8b260f9a10b0459aa441ad8588c2251c_0/about

ACS Income Data for Seattle - https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::per-capita-income-and-aggregate-income-in-the-past-12-months-in-inflation-adjusted-dollars/explore

TIGER/Line Shapefile, All Roads, King County - https://catalog.data.gov/dataset/tiger-line-shapefile-2021-county-king-county-wa-all-roads