## Project Description
This projet ueses data on Coronavirus cases in every county in the U.S and Census Bureau data on the characteristics of those counties in order to create visualizations and potentially identity characteristics of counties that were able to contain the spread of Coronavirus. 


## Study design and data processing

### Collection of data
Data was collected from USAFacts and the American Community Survey.

### Descirption of data
First economic and demographic data on every county in the United States from the American Community Survey were be uploaded into the Jupyter Notebook as well as mask wearing data from the New York Times and Coronavirus case data on every county from USAFacts. These data will then be merged into a single DataFrame by matching the codes of each county. https://github.com/twarnemiagh/Fall-2020-Independent-Study/tree/main/Datasets

## Description of the variables
Datasets can be found in the data file:

### DP03_0119PE 
Poverty rate in each county.
 - Numeric percent estimate

### DP03_0062E
Median household income in each county.
 - Numeric dollar estimate
 
### DP03_0099E
Percent of population with no health insurance in each county.
 - Numeric percent estimate

### DP03_0021PE
Percent of population using public transportation to commute to work in each county.
 - Numeric percent estimate

### DP05_0017PE 
Percent of population that is 85 years or older in each county.
 - Numeric percent estimate

### DP02_0064PE
Percent of population with a bachelor's degree in each county.
 - Numeric percent estimate
 
### DP05_0038PE
Percent of population that is black or african-american in each county.
 - Numeric percent estimate

### DP05_0039PE
Percent of population that is american indian or alaska native in each county.
 - Numeric percent estimate
 
### case_rate
Rate of cases in each county calculated by diving confirmed cases in a county by the total population in that county.
 - Numeric percent estimate
 
### mask_rarely-never
The addition of the proportions of people who wear a mask rarely or never in each county.
 - Numeric percent estimate

### mask_always
The proportion of people who wear a mask always in each county.
 - Numeric percent estimate
 
### dom_party
The dominate party affliation in each county in the state of Pennsylvania. The variable takes the value democratic majority if there were more total democratic votes otherwise it takes the value republican majority.
 - Categorical binary label
 


## Sources
Datasets from the American Community Survey: 
https://data.census.gov/cedsci/table?g=0100000US.050000&d=ACS%205-Year%20Estimates%20Data%20Profiles&tid=ACSDP5Y2019.DP05&hidePreview=false

Dataset from USAFacts: 
https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/

Dataset from New York Times:
https://github.com/nytimes/covid-19-data/tree/master/mask-use
