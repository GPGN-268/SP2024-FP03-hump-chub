# SP2024-FP03-hump-chub
## Project Title : Characterizations of Humpback Chub Populations

## Team Member Names and GitHub Handles
Eliza Ross (@elizaross104)
<br>Katie Gonzalez (@katgonza)
<br>Anna Melega (@amelega)

## Short 1-2 sentence summary
We aim to compare population and size data for the Humpback Chub to precipitation in the Colorado River basin. 

## Some introductory background information
The Humpback Chub is a native species of fish of the Colorado River Basin, protected under the Endangered Species Act due to the effects of dams and human water use on river flow & habitat. As precipitation changes due to climate change and other effects, it is important to understand how changing levels in precipitation will affect species populations and the greater ecosystem. 

## Problem statement, question(s) and/or objective(s)

As climate change affects weather patterns across the globe, annual precipitation is expected to change as well. Stories of water shortages and long term droughts already fill headlines as reservoirs hit historic lows. The two largest reservoirs in the world, Lake Powell and Lake Mead, are fed by the Colorado River Basin, with the effects of long term droughts already impacting the millions of people that depend on its water. Other creatures also depend on the Colorado River Basin for survival, notably species of fish like the humpback chub that are only found in the Colorado River. Federally protected and classified as endangered, the chub has seen rapidly declining populations since the building of dams on the Colorado River in the 1970s. This raises the question: how will the humpback chub respond to a changing climate? More particularly, will the population change and will growth be affected by a change in precipitation? We will compare population size and average chub length to precipitation in the Colorado River Basin with the goal of understanding how the chub will respond to climate change.

## Datasets you will use (with links, if available)

Humpback Chub and Rainbow Trout Joint Mark-Recapture Data and Model, Colorado River, Arizona: https://doi.org/10.5066/f7zc81t9

Humpback chub (Gila cypha) capture histories and growth data for two areas in the Colorado River network from 2009-2022 and 2017-2022: https://www.usgs.gov/data/humpback-chub-gila-cypha-capture-histories-and-growth-data-two-areas-colorado-river-network

Humpback chub (Gila cypha) and mean daily water temperature data, western Grand Canyon - 2000 to 2016: https://www.usgs.gov/data/humpback-chub-gila-cypha-and-mean-daily-water-temperature-data-western-grand-canyon-2000-2016

Water temperature models, data and code for the Colorado, Green, San Juan, Yampa, and White rivers in the Colorado River basin: https://doi.org/10.5066/P9HFKV7Q

USGS 09402000 LITTLE COLORADO RIVER NEAR CAMERON, A
https://waterdata.usgs.gov/nwis/monthly/?site_no=09402000&referred_module=sw&format=sites_selection_links

USGS 09402300 LITTLE COLORADO RIVER ABV MOUTH NR DESERT VIEW, AZ
https://waterdata.usgs.gov/nwis/monthly/?site_no=09402300&referred_module=sw&format=sites_selection_links

USGS 09402500 COLORADO RIVER NEAR GRAND CANYON, AZ
https://waterdata.usgs.gov/nwis/monthly/?site_no=09402500&referred_module=sw&format=sites_selection_links

USGS 09403850 KANAB CREEK ABOVE THE MOUTH NEAR SUPAI, AZ
https://waterdata.usgs.gov/nwis/monthly/?site_no=094038500&referred_module=sw&format=sites_selection_links


## Tools/packages

Jupyter Notebook
scikit-learn
pandas
matplotlib.pyplot
XML Workbook converters

## Planned methodology/approach

**Data Collection**: <br>
	Humpback chub population sizes<br>
    Average chub length<br>
    Historical precipitation data for Colorado River Basin

**Data Cleaning and Prep**:<br>
    Format conversions, especially for historical data, for compatibility<br>
    Remove inconsistencies, outliers<br>
    Remove irrelevant data used for other research

**Exploratory Data Analysis (EDA)**:<br>
	Use descriptive functions to understand size/breadth of datasets<br>
    Use histograms, scatter plots, time series plots to visualize datasets<br>
    *Statistical Analysis*: Correlation analysis, regression analysis (maybe), understand the strength of relationship
		C. B. YACKULIC ET AL<br>
            Closed models, which assume population closure during the study<br>
            Open models to allow for gains and losses to the local population over the period of data collection
	
**Modeling**:<br>
		Predictive models to forecast Humpback Chub population dynamics based on precip. data<br>
        Time series analysis, regression models, machine learning algorithms for complex relationships
	
**Validation/Interpretation**:<br>
		Validation scores of models are optimized<br>
		Identify potential mechanisms for driving observed patterns

## Expected outcomes
### Present or anticipated challenges:
Using files in the format of XML Workbooks
Historical data for precipitation, but much smaller time series for humpback chub data

## Any other relevant information, images/tables, references, etc.

## References

Yackulic, C.B., Korman, J., Yard, M.D. and Dzul, M. (2018), Inferring species interactions through joint mark–recapture analysis. Ecology, 99: 812-821. https://doi.org/10.1002/ecy.2166

Colorado River Basin Climate and Hydrology: https://wwa.colorado.edu/sites/default/files/2021-06/ColoRiver_StateOfScience_WWA_2020_Chapter_2.pdf
