## Part 2 of Census Data Workshop

Click here to see [Part 1](README.md)

## Race and ethnicity data, by counties

- 2017 ACS5 median-household-income-by-race, by counties: [http://bit.ly/purplegolf](http://bit.ly/purplegolf)
- How do we tidy it?
- How do we [wrangle it](https://docs.google.com/spreadsheets/d/1Q9n8bgFQkts8-hpyEatwLJ4BWCQYzd1oYpmrwKHKs0o/edit#gid=930696376)? 
- Make choropleths: [black household incomes compared to white by county](https://www.datawrapper.de/_/IS6hS/)


<img src="docs/homeassets/images/map-bw-median-incomes.png" alt="">



### Optional: How to upload custom mapfiles to Datawrapper

This is getting into advanced territory, but it may be worthwhile to get it in your head how shapefiles exist for every Census geographic region, and that there exist tools to make it work for you.


- Get tract-level Chicago data as GeoJSON: https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Census-Tracts-2010/5jrd-6zik
- Follow [Datawrapper's guide to simplifying the GeoJSON](https://academy.datawrapper.de/article/145-how-to-upload-your-own-map) using [mapshaper.org](https://mapshaper.org/)
- Or download my [copy of it](https://drive.google.com/open?id=1pbtWTp8f_s_RMBTJdCDd8dArBs_WRjpC)
- [Download ACS5-2017 tract level race and ethnicity data](https://docs.google.com/spreadsheets/d/1OlgpKRNztpPK-Ln6wxRUtV_BW6AfcKnWWq3n1rzU20g/edit#gid=0)

## How to fetch data from FactFinder and data.census.gov

- Go in knowing that the data you want exists, maybe the survey/table where it came from, and ideally, a specifically value to spot-check (i.e. use CensusReporter)



### American FactFinder strategy

Go to [Advanced Search](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml?refresh=t)

- First, choose the smallest geographical region you want to work with. The smaller the geo-category, the less data options you have (e.g. ACS-1-year does not exist for Census tracts, or small towns)
- Then search by the general topic ("race" or "poverty")
- Filter by year
- Finally, browse the results and select the table that best fits what you need

### data.census.gov

Maybe? (site seems down, randomly) https://data.census.gov/cedsci/advanced




