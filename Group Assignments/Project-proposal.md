# Project Proposal

#### *Arturo Jacobo and Miranda Mead-Newton*

## Project Vision
#### Did the NextGen bus plan improve job accessibility for those who rely on the Metro bus network in the City of LA?
For our research project, we would like to explore the effects of the NextGen bus plan on job accessibility for those who rely on the Metro bus network in the City of LA. Our interest stems from a concern with transit access, job access, and equity. According to LA Metro, the median household income of bus riders in the County of Los Angeles in 2019 was $17,975 and 57% of riders lived below the poverty line. The bus in LA is most relied upon by those with the lowest incomes and the least job flexibility, thus an equitable bus system must take into account the needs of the most disadvantaged residents of the City of LA. In December 2020, LA Metro introduced a new bus system called the NextGen Bus Plan that took into account an extensive outreach process and was intended to be paired back and more efficient. We are interested in how well the NextGen LA Metro bus system is serving the most transit-dependent communities, specifically in terms of their ability to access jobs within a reasonable commute time. This is also a pivotal moment for public transportation. Transit ridership has gone down in recent years and a more effective bus route would encourage greater usage and take cars off the road. Considering the effects of climate change, it is imperative that we introduce an effective transit system in LA and shift away from single occupancy vehicle use. 

## Methodology and Scope
#### Plan A (Ambitious):
We are thinking of “accessibility” as it is used in the field of transportation planning. In this context accessibility is a measure of the number of activity sites (in this case jobs) and the distance between a person and those activity sites, taking into account travel time. Within the literature there are many different formulas for measuring accessibility for a public transit network that take into account number of activity sites, walk time, headways (bus frequency), and total trip time. We plan to adapt one of these formulas, using total number of jobs per census tract as the activity sites and restricting travel to a 30-minute trip. A 30-minute trip will simplify our study and is commonly used in the research because it is seen as an ideal commute time. Using these datasets, we will be able to arrive at a quantitative number for each census tract in the City of LA that represents the degree of job accessibility via the bus network. We will create a map of job accessibility via bus in LA for each bus system (NextGen and the original bus system). Each choropleth map will have a numeric value assigned to a census tract. We will then create a third map that will represent the difference between the two bus systems. This map will tell us where accessibility has increased and decreased and can be compared with a choropleth map of median incomes in the City. Using the map of median incomes, we will be able to see how low income areas of the City will be affected by the bus route changes in their ability to access jobs. 
We have decided to restrict our study to just the City (not the County) because we want to look at LA Metro’s bus network. Including other cities would necessitate the inclusion of many different bus networks and systems and may over complicate the study. Also, the local bus network is more relied upon by those who live in the city center than those who live further away. 
#### Plan B (Paired Back):
If this proves to be too ambitious, we can remove the variable of bus frequency and just look at the number of jobs that can be accessed via the bus from a given point in a 30 minute trip. We are hoping to take into account walk time in our 30-minute trip (e.g. 10 minute walk to a bus station + 20 minute bus ride). If we need to make this simpler, we can measure distance “as the crow flies” (directly) instead of by a more realistic walking route. We also may find it to be too ambitious to analyze both bus systems. If this seems unrealistic, we will just analyze the NextGen bus system. We will be able to compare the NextGen bus job accessibility analysis with a map of bus lines that were removed or reduced in frequency. This would likely be sufficient in helping us to analyze the effectiveness of the NextGen bus network. 

## Datasources
#### LA Metro bus data
- [NextGen: Bus Routes, bus stops, headways (bus frequency, if we decide to include this)][NextGen and old bus route data]
- [Original Bus Route: Bus Routes, bus stops, headways (bus frequency, if we decide to include this)][NextGen and old bus route data]

#### Census Data
- Number of jobs per Census tract (link to come, but should be available via the census website)
- [Average income by Census tract][census income]

[NextGen and old bus route data]: (https://www.metro.net/projects/nextgen/nextgen-data-and-analysis/)
[census income]: (https://data.census.gov/cedsci/table?t=Income%20and%20Poverty&g=0500000US06037.140000&tid=ACSST5Y2019.S1903&hidePreview=true)
