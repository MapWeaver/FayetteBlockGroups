# Project proposal

## TOPIC/GEOGRAPHIC PHENOMENA

I am focused on statistical information for Fayette County, the city with which I am employed as a Planner Senior. With this, the more I can understand and the more I can effectively communicate to others, the more informed I will be.

## TITLE

The name "Fayette County 2016 Block Group Statistical Exploration" may not be as exciting to others as it is for me but it does explain what I desire to show. Perhaps that could serve rather as the subtitle and a more provocative title could be used. Maybe something like "Deep Data Dive" given that BG level data is a challenge to analyze for the general population given the Census Bureau does not make that readily available in a  web map.


## THEMATIC REPRESENTATION

Thematically, this data lends itself to a chloropleth map of the block group polygons. Gradients will likely be based around quantile or natural jenks classification depending on what appears most useful to the end user based on the content of the data.  

## MAP OJECTIVES

Why I Am Making This Map: To provide users with a deeper look at informative data at the block group level, a level more obscure and less likely to be evaluated.

## USER NEEDS/INTERACTION

**User Persona**: A community activist wishes to get a better grasp of the discrepancies across the city. Knowing that the county and tract level information available through the Census Bureau is not sufficiently granular for their needs, they seek block group level data. Community Activist is excited to find that the information has already been made available through this map and even more stoked to be able to toggle between various stats. They walk away with a better understanding of the city and more empowered to improve the world around them.


## CONTENT REQUIREMENTS

* toggle between statistical data sets to see the chloroplethed results
* mouseover functionality to show what all of the stats available for the BG
* pop-ups that stay engaged until closed and show the median values for the county next to the value for the selected block group
* ability to use at least 2 basemaps
* print to pdf with metadata information


## TECHNOLOGY STACK

* Data/Info Processing Tools: QGIS, MapShaper,
* Data Format: GeoJSON
* JS Libraries: Bootstrap, Skeleton, FontAwesome, Leaflet Omnivore, Simple Statistics
* Other Relevant Web Tech: HTML, CSS, Leaflet, D3, ES6
* Hosting Platform: Github


## DATA SOURCE

In this module, I have chosen to continue with the data I struggled to format in assignment 2.

I narrowed the extent of the block group level data down to exclusively Fayette County. Data is from the Census/American Community Survey.

This data has already been converted (I think successfully) to geojson/topojson and is living in the lab data folder for this module.
