# Visualizing the number of reported deaths of COVID-19 in sub-Saharan African


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About this repository](#about-the-project)
* [Charts](#charts)
* [Getting Started](#getting-started)
* [License](#license)
* [Contact](#contact)
* [Contributing](#contributing)



<!-- ABOUT THE PROJECT -->
## About this repository

As part of the [Economics for Transformation](https://www.econfortransformation.org/) network, me and my team have been creating different ways to visualize the evolution of the COVID-19 pandemic during 2020 in Sub-Saharan Africa, while monitoring the situation in many of the region's countries.

We try to update the charts on a daily basis taking the numbers from the [COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19) that feeds the [dashboard](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6) that has been widely cited and used by multiple institutions and researchers.

While Sub-Saharan African region (SSA) started to record their first cases and deaths from COVID-19 weeks later than Asia, North America and Europe and testing and reporting has not been as consistent as in other parts of the world, it is important to observe any alarming signals from the data. For example, South Africa, the first country in SSA to report over 100 cases on March 18, did so one month after Italy and two weeks later than the United States and now is between the 10 countries with the highest number of reported cases.

In this repository I modified the code to show the number of reported deaths instead of the [code that creates charts showing reported cases](https://github.com/alexis-ribal/covid19_africa) that are posted in the [blog post](https://www.econfortransformation.org/reported-cases/) in the [Economics for Transformation](https://www.econfortransformation.org/) site.  We encourage the public to share these charts and for those who are interested, use the model code to run their own analysis.

The code to create the chart can be found [here](https://github.com/alexis-ribal/covid19_africa_deaths/blob/master/scripts/covid19_africa_deaths.do) and the high-resolution charts can be found [here](https://github.com/alexis-ribal/covid19_africa_deaths/tree/master/charts).

*The numbers for reported cases is here https://github.com/alexis-ribal/covid19_africa_deaths*


### Charts

![Cumulative deaths by region](/charts/regions_cumu_deaths.png)
![Cumulative deaths per million people by region](/charts/regions_pc_deaths.png)
![Reported deaths by country](/charts/deaths_bar.png)
![Cumulative reported deaths by country](/charts/countries_cumu_allssa_deaths.png)
![Daily reported deaths in SSA and South Africa](/charts/new_daily_deaths.png)
![Daily reported deaths by region](/charts/new_daily_deaths_region.png)


<!-- GETTING STARTED -->
## Getting Started

To reproduce these charts you need at least Stata 13 or a more recent version.  All these charts were created using Stata 15.

In Stata you will need to install the following packages:

* The [World Bank Open Data API](https://blogs.worldbank.org/opendata/accessing-world-bank-open-data-stata).
```sh
install wbopendata
```

## License

The image and the code can be used under the [CC-BY](https://creativecommons.org/licenses/by/4.0/) license which requires attribution to the author.


## Contact

If you have any question about this repository or the charts displayed here, please contact ariveraballester@worldbank.org


## Contribuiting

If you would like to contribute by creating other striking visualizations or suggest changes to these, please contact ariveraballester@worldbank.org
