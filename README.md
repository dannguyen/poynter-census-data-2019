# Poynter Census Data Workshop 2019

## repo-shortlink: [bit.ly/cdata2019](https://bit.ly/cdata2019)

This repo contains slides and notes for the "Hands-on Data Training" session for [Poynter's Covering the Census Workshop held on June 7, 2019](https://www.poynter.org/covering-the-census-chicago/#1549662376277-7e2acdf9-0a298297-4e4f), sponsored by the [McCormick Foundation](https://donate.mccormickfoundation.org/)


To get to this page via short URL, use: [bit.ly/cdata2019](https://bit.ly/cdata2019)





## Starters

- Should probably sign up for a Google Account (to use Google Sheets) if you don't have one by now
- Visit [https://censusreporter.org](https://censusreporter.org) and fill out this little anonymous data collection form (to be analyzed as an example in class): [http://bit.ly/zipgform](http://bit.ly/zipgform)
- [Optional] Sign-up for a free [datawrapper.de account](https://www.datawrapper.de/) to make visualizations


## Exploring CensusReporter 

Open and browse the pages for:

- [The United States](https://censusreporter.org/profiles/01000US-united-states/)
- [Illinois](https://censusreporter.org/profiles/04000US17-illinois/)
- [Chicago](https://censusreporter.org/profiles/16000US1714000-chicago-il/)
- [Census Tract 3201, Cook, IL](https://censusreporter.org/profiles/14000US17031320100-census-tract-3201-cook-il/) which is the tract for the address [205 North Michigan Avenue, Chicago, Illinois 60601,](https://censusreporter.org/locate/?lat=41.886024&lng=-87.623542&address=205%20North%20Michigan%20Avenue,%20Chicago,%20Illinois%2060601,%20United%20States)
- Some other town/city not Chicago (e.g. where you lived before moving here, or where you last visited)

Take notice at:

- Look at what data points are emphasized by CensusReporter
- Look at how data changes in quality/interest-level as you move from one geographic category to another
- Compare what the Census data says to what you assume about these places


### Slides: Exploring data presentation in CensusReporter and elsewhere

Census data is so overwhelming that it's best to use a site like CensusReporter as a navigation tool to what is important (or worth prioritizing), how things are labeled, and where data can be found:

https://dannguyen.github.io/poynter-census-data-2019/slides/content/exploring-census-reporter


-------------------------

### Spreadsheet warmup with our collected data

> Note: the best thing you can do to understand data is to get [familiar with spreadsheets](https://multimedia.journalism.berkeley.edu/tutorials/spreadsheets/) and use them as often as possible (more than daily!). That's the most important skill, but we won't have time to get through it in this workshop.

The class data from the [Google Form](http://bit.ly/zipgform) should be here to use:

http://bit.ly/warmzipcode


#### Spreadsheeting our data collection 

- Make a copy of the spreadsheet for yourself (so you can edit it)
- Make a column that shows the percentage-point difference between the "White %" values of people's "work area" and their "origin zip code"
- Make a column that shows the ratio of origin-zip-code median household income to work-area-median-household-income
- Try to make a visualization from these derived columns






------------------------

## Cleaned-up Census Data warmup http://bit.ly/blueredhello

The hardest part of data work is the data-wrangling (aka data cleaning). Rather than jump into the confusing mess that the Census data can often be, we start with a simplified, cleaned-up version of the original data, as to be familiar with the principles of tidy data:

The spreadsheet at [http://bit.ly/blueredhello](http://bit.ly/blueredhello) contains cleaned up **state-level data** from two sources: 

- Census: the state-level 2017 ACS-1-year DP03 (selected economic characteristics) data: http://bit.ly/2017econstates
- Elections: Data [courtesy of Dave Leip's Atlas](https://docs.google.com/spreadsheets/d/1VWo5ZuNIFZ726I5bfmDJwBlGEjd43qR3nuCDKY9-_vE/edit#gid=1312827112) / http://bit.ly/leip2016copy

### Brief chart basics

Try to make some charts from [http://bit.ly/blueredhello](http://bit.ly/blueredhello) using Google Sheets. An example workbook can be found here: https://docs.google.com/spreadsheets/d/13YknXg46P6NVA-1dRFYVAbFQQxmEdG0YSiDmU2uKgxE/edit#gid=1536535436

> The more you understand how to "manually" (e.g. [with LEGOS](https://ajr.org/2015/02/02/journalism-professors-used-legos-teach-super-bowl-data-visualization/)), the sooner you'll grok the patterns and best practices in data visualization...

<img src="docs/homeassets/images/2016-r-v-d-bars.png" alt="2016-r-v-d-bars.png">



## Charts in datawrapper

Data visualization tools all have varying features, but they have the same principles when it comes to structure of data (rows and columns, essentially).


Try to make: [Poverty bar chart colored by state presidential vote](https://river.datawrapper.de/_/ohOGU)

Import the data from [http://bit.ly/blueredhello](http://bit.ly/blueredhello) into DataWrapper


## Choropleth map basics

One of the best features of datawrapper.de is its easy-choropleth-mapping (density maps)

Copy-paste data found at: http://bit.ly/blueredhello

Let's make:

- a [U.S. map of the states shaded by 2016 electoral results](https://datawrapper.dwcdn.net/oFPwJ/1/)
- a [U.S. map of the states shaded by poverty rate or median household income](https://datawrapper.dwcdn.net/W5vyS/1/)


## Story time

A few examples of Census data used in news reporting:

https://dannguyen.github.io/poynter-census-data-2019/html/content/story-census-ideas/


## BREAK --------------------------------


## Go to [Part 2](part-2.md)

[Go to Part 2](part-2.md)
