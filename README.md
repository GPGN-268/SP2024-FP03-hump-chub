# Characterizations of Humpback Chub Populations Affected by Streamflow
**Repository Name**: SP2024-FP03-hump-chub

## Project Overview
This project aims to analyze the impact of changing precipitation patterns on the population and size distribution of the Humpback Chub in the Colorado River Basin. Given climate change and its potential impact on streamflow, our study intends to establish a relationship between precipitation changes and Humpback Chub populations.

## Team Members
Eliza Ross ([Github](https://github.com/elizaross104)
<br>Katie Gonzalez ([Github](https://github.com/katgonza))
<br>Anna Melega ([Github](https://github.com/amelega))

## Background
The Humpback Chub is a native fish species in the Colorado River Basin, listed under the Endangered Species Act due to habitat loss caused by dams and human water use. As climate change affects weather patterns and streamflow, it is crucial to understand the potential impacts on this endangered species.

## Objectives
* Wrangle and process data for Humpback Chub characteristics and streamflow discharge in the Colorado River.
* Understand the correlation between streamflow changes and chub population characteristics.

## Requirements and Problem Statement

As climate change affects weather patterns across the globe, annual precipitation is expected to change as well. Stories of water shortages and long term droughts already fill headlines as reservoirs hit historic lows. The two largest reservoirs in the world, Lake Powell and Lake Mead, are fed by the Colorado River Basin, with the effects of long term droughts already impacting the millions of people that depend on its water. Other creatures also depend on the Colorado River Basin for survival, notably species of fish like the humpback chub that are only found in the Colorado River. Federally protected and classified as endangered, the chub has seen rapidly declining populations since the building of dams on the Colorado River in the 1970s. This raises the question: how will the humpback chub respond to a changing climate? More particularly, will the population change and will growth be affected by a change in river discharge? We will compare population size and average chub length to water discharge in the Colorado River with the goal of understanding how the chub will respond to climate change.

## Datasets
1. **Species Data** <br>
[Humpback Chub and Rainbow Trout Joint Mark-Recapture Data and Model, Colorado River, Arizona](https://doi.org/10.5066/f7zc81t9) <br>

[Humpback chub (Gila cypha) capture histories and growth data for two areas in the Colorado River network from 2009-2022 and 2017-2022](https://www.usgs.gov/data/humpback-chub-gila-cypha-capture-histories-and-growth-data-two-areas-colorado-river-network) <br>

[Humpback chub (Gila cypha) and mean daily water temperature data, western Grand Canyon - 2000 to 2016](https://www.usgs.gov/data/humpback-chub-gila-cypha-and-mean-daily-water-temperature-data-western-grand-canyon-2000-2016) <br>

2. **Environmental Data** <br>
[USGS 09402000 LITTLE COLORADO RIVER NEAR CAMERON, AZ](https://waterdata.usgs.gov/nwis/monthly/?site_no=09402000&referred_module=sw&format=sites_selection_links) <br>

[USGS 09402300 LITTLE COLORADO RIVER ABV MOUTH NR DESERT VIEW, AZ](https://waterdata.usgs.gov/nwis/monthly/?site_no=09402300&referred_module=sw&format=sites_selection_links) <br>

[USGS 09402500 COLORADO RIVER NEAR GRAND CANYON, AZ](https://waterdata.usgs.gov/nwis/monthly/?site_no=09402500&referred_module=sw&format=sites_selection_links) <br>

[USGS 09403850 KANAB CREEK ABOVE THE MOUTH NEAR SUPAI, AZ](https://waterdata.usgs.gov/nwis/monthly/?site_no=094038500&referred_module=sw&format=sites_selection_links) <br>

[NCEI THREDDS Data Server Topography](https://www.ngdc.noaa.gov/thredds/catalog/global/ETOPO2022/60s/60s_bed_elev_netcdf/catalog.html?dataset=globalDatasetScan/ETOPO2022/60s/60s_bed_elev_netcdf/ETOPO_2022_v1_60s_N90W180_bed.nc)

## Tools and Libraries
To conduct our analysis, we used the following tools and libraries:
* Jupyter Notebook
* scikit-learn
* pandas
* matplotlib.pyplot
* XML Workbook converters

## Methodology

**Data Collection**:
* Average chub length
* Number of chub caught
* Streamflow discharge on the Colorado River in Arizona

**Data Cleaning and Prep**:
* Format conversions, especially for historical data, for compatibility
* Skip metadata during loading
* Remove inconsistencies, outliers
* Remove irrelevant data used for other research

**Exploratory Data Analysis (EDA)**:
* Use descriptive functions to understand size/breadth of datasets
* Use histograms, scatter plots, time series plots to visualize datasets
  * *Statistical Analysis*: Correlation analysis, regression analysis (maybe), understand the strength of relationship
    * C. B. YACKULIC ET AL.
    * Closed models, which assume population closure during the study
    * Open models to allow for gains and losses to the local population over the period of data collection
		
**Validation/Interpretation**:
* Validation scores of models are optimized
* Identify potential mechanisms for driving observed patterns

## Summary of Results

Using data describing discharge of the Colorado River over time, as well as number of Humback Chub caught and their lengths, we found a correlation between increased discharge and increased size of chub. Detailed figures and analysis can be found [here](scripts/final.ipynb). 

## References

Yackulic, C.B., Korman, J., Yard, M.D. and Dzul, M. (2018), Inferring species interactions through joint mark–recapture analysis. Ecology, 99: 812-821.[DOI Link](https://doi.org/10.1002/ecy.2166)

[Colorado River Basin Climate and Hydrology](https://wwa.colorado.edu/sites/default/files/2021-06/ColoRiver_StateOfScience_WWA_2020_Chapter_2.pdf)
