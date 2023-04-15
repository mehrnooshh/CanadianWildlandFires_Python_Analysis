# CanadianWildlandFires_Python_Analysis
![image](https:)

Sourcing an open-source dataset in order to meet the different criteria. We selected Canadian Wildland Fires data which is accessible through CWF Information System Datamart, however, the contents of this project have been fabricated for the purpose of learning. 

We will be conducting the following analyses via Python:
- Exploratory analysis through visualizations (scatterplots, correlation heatmaps, pair plots, and categorical plots)
- Geospatial analysis using a shapefile
- Regression analysis
- Cluster analysis
- Time-series analysis
- Analysis narrative and final results (presented in a Tableau story)

# Objective
Canada has about 9% of the world’s forests. Each year over the last 25 years, about 7,300 forest fires have occurred. The total area burned varies widely from year to year but averages about 2.5 million hectares annually.

Some are uncontrolled wildfires started by lightning or human carelessness. A small number are prescribed fires set by authorized forest managers to mimic natural fire processes that renew and maintain healthy ecosystems.

Wildland fires present a challenge for forest management because they have the potential to be at once harmful and beneficial. Forest agencies work to harness the force of natural fire to take advantage of its ecological benefits while at the same time limiting its potential damage and costs. This makes fire control strategies a vital component of forest management and emergency management in Canada. We would like to help Canadian Forest Service (CFS) by analyzing fire characteristics so they can prioritize and improve timing, locations and etc. 

- Only 3% of all wildland fires that start each year in Canada grow to more than 200 hectares in area. However, these fires account for 97% of the total area burned across the country.

- Fire suppression costs over the last decade in Canada have ranged from about $800 million to $1.5 billion a year [(from)](https://natural-resources.canada.ca/our-natural-resources/forests/wildland-fires-insects-disturbances/forest-fires/13143).

# Data:
- Citation: [Canadian Wildland Fires](https://cwfis.cfs.nrcan.gc.ca/datamart) , Last update on 31 Dec 2021
- Available on [Kaggle](https://www.kaggle.com/datasets/ulasozdemir/wildfires-in-canada-19502021)

# Tools
For this project, the following Python libraries were used:
+ Pandas- for data analysis
+ Seaborn- for visualization
+ Matplotlib - for visualization
+ Geopy- for calculating the distance of locations by latitude and longitude
+ Json- for importing and working with geoJson files
+ Folium- for analyzing the location and geospatial data and creating interactive maps
+ Sklearn- for using machine learning algorithms like classification, regression, and clustering
+ Statsmodels- for time series analysis
