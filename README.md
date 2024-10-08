# Analysis of water supply interruptions by populated areas on the territory of Dobrich Water Supply and Sewage

## Abstract
The following project consists of several stages. Acquisition of data, cleaning and arrangement for incidents related to interruption of water supply in the territory of Dobrich district. Geographic visualization and clustering.

## Data acquisition
The raw data has been scraped from the Water Supplier web site. Then it has been transformed into usable csv files.

## Geographic visualization

Here is a map with date picker filter to visualize the water interruptions in a 7 year period
![Map of water supply interruptions by day for 7 year period](images/dobrich_water_interruptions.png)

## Clustering the geographic regions
We used a k-means clustering algorithm to find existing points with similar water supply interruption behaviour.
![Clusters of Water Supply Interrruptions](images/dobrich_water_interruptions_clusters.png)

## How to use
Open the .ipynb file with Jupyter Notebook. 