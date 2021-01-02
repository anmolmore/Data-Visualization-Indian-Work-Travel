## Visualizations (Key Findings)

### Majorly people travel for work purpose, Major transport modes – Bus, Trains, 2 Wheelers, Cars

### How Indians Travel to work ?
•	Cycle to work is healthy – But 20-40 KMs daily Isn’t. A large population including females can be seen.

•	In Urban population, Ladies travel more by train/ buses and Men by Two wheelers.

•	In Rural population, Ladies travel mostly on foot, Men dependent on bus connectivity.

### Cars/ Two Wheelers usage ?
•	Bangalore and Pune have 9.5 and 8+ Lakhs people traveling by private vehicles to work everyday

o	Need more buses to reduce traffic/pollution and ease of traveling

•	Bangalore alone has more people traveling by Car, than whole of NCR or even populated Mumbai 

o	Shows cities like Mumbai and Delhi have benefitted lot from suburban rail and metro

•	Next on list, we have Chennai, Surat and Ahmedabad

o	5+ Lakhs cars/bikes on road everyday

### Lack of Connectivity in Urban areas
•	24 Parganas (West Bengal) lacks most in connectivity

o	People forced to travel on Foot/Cycle 10-40 KMs everyday for work

o	Need connectivity in both Urban and Rural areas

•	Mumbai Suburban, Bangalore and Ahmedabad each have 2.5 Lakhs people traveling on Foot/Cycle to work

o	Needs better connectivity/ wider roads

o	Deployments of additional bus routes

### Dataset
•	Dataset collected from Indian Government’s public data repository - https://data.gov.in/catalog/other-workers-distance-residence-place-work-and-mode-travel-place-work-census-2011-india-and

•	Data on residence to place of work travel (whole population except agricultural and household working population)

•	State and city level data for remotest areas of India based on distance and all possible transport modes

•	Important rows – 
  
  o	Division of Urban and Rural population
  
  o	Male/ Female population census
  
  o	Bucketed distance 0-1, 2-5, 6-10 Kms and so on

### Data Cleaning and Preparation

•	Python scripts to combine and clean data

•	Google Maps APIs used to fetch Latitude and Longitude for each city/ area

•	Scripts and data available at - https://github.com/anmolmore/Indian-Work-Travel (available on request/not public)

•	Filtered duplicated data for total counts and edited misspelt city names•	20k rows and 36 columns after combining data from each state and union territory
