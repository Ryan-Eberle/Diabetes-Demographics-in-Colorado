# Diabetes-Demographics-in-Colorado
Visualization project of diabetes rates along Age, Income, Food Security, and Urban/Rural settings. 

## Motivation
Effectiveness in health awareness programs and education come from a greater understanding of the demographics involved. By indentifying target areas within the population, health and food resources, prevention and treatment programs can be aimed with greater precision.

We believe that the stated variables of age, income, food security, urban/rural setting have an effect on the rates of diabetes amongst the population of Colorado. 

## Goal 
By visualizing the demographics of Colorado along age, income, food security, and urban/rural settings as they pertain to diabetes rates, the aim is to identify areas within the state's population that would benefit from allocation of resources and education. 


## Data

Data Sources: USDA Food Environment Atlas Data for Colorado Census Tracts (2017), Diabetes in Adults - CDPHE Community Level Estimates (Census Tracts) (2014-2017),  Diabetes Hospitalization Rate (Census Tracts) (2013-2017), Income/Poverty (Census Tracts) (2014-2017) , Current Prevalence of Diabetes - Center for Disease Control(2011-2020), Educational Attainment (Census Tracts) (2013-2017).  All resources were accessed from CDPHE Open Data:  https://data-cdphe.opendata.arcgis.com/

Using the above sources, the data will be visualized across multiple charting methods. 

## Urban vs. Rural Diabetes and Hospitalization Rates
Rural and urban Coloradans have roughly equivalent average diabetes rates (8%).  However, urban Coloradans are hospitalized for diabetes far more often than rural Coloradans (+20%).  We conjectured that distance to a hospital may account for why rural diabetics are hospitalized less often than urban diabetics.  Looking into this, we mapped hospital locations in reference to rural and urban census tracts, and differences were not significant.  

While rural Coloradans do have less access to hospitals in terms of distance, that doesn't explain why hospitalizations per 100,000 people occur at a much greater rate in urban areas.  We conjecture that people in urban areas may have less access to consistent care in terms of yearly checkups and prescription compliance and may have lower insured rates, leading to more complications and hospitalizations.  

Additionally, there is a slightly higher correlation between almost all access-impairing factors (income, distance, education) and both hospitalization per 100,000 and estimated diabetes rates (%) in urban census tracts, suggesting that the higher hospitalization rate in urban areas may be connected to a compounding of access-imparing issues.  This study could be furuther pursued by adding in census data regarding rural and urban insured rates and by looking at compounded access-imparing factors.  Insured data is available from the Small Area Health Insurance Estimates (2018) dataset from the Census Bureau.  

## Diabetes Rates along LILA rated census tracts
Low Income(LI) rankings are determined by poverty rates(at least 20%) or median family income ( at or below 80% of metropolitan area or the state's median income.

Low Access(LA) status is measured in four different ways. The first three are based on the distance to the nearest supermarket or grocer. The distance thresholds for urban ares is 0.5 and 1 mile, while rural areas are measured at 10 and 20 miles. The last measure is based on household without access to a vehicle that live over 0.5  miles

Colorado has 52.9% of it's census tracts with no LILA designation. That represents 3,701,428 residents of Colorado's 5,395,805 total population. This analysis will compare their rates of diabetes along their population sizes.  

There was a slight negative correlation between the diabetes rates and the population size of each LILA tract group, this was also showed in the census tracts that did not have a LILA designation though not as strongly. Given the weight of the Non-LILA tracts it was worth investigating where that correlation was coming from. The variance among the data points in the lower population tracts gave a path for the data to determine where that variance would come from. 

Seperating the data along the Urban/Rural designation in each LILA tract allowed for more visualization of where the variance was occuring. The lower population rural tracts showed significantly higher rates of diabetes rates. Adding health and education resources per capita would allow for a clearer view of how these affected tracts are being managed from a medical perspective. 
