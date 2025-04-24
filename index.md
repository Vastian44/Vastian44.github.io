---
layout: default
---

*By Bastian Gulstad Ravn (s214727)* 

* * *
* * *

Gun crime is a major topic in modern America. In 2023, nearly 47.000 people in the US died from gun related injuries [[1]](https://www.pewresearch.org/short-reads/2025/03/05/what-the-data-says-about-gun-deaths-in-the-us/). Compared to other large western nations, the US has significantly higher rates of gun violence. For example, firearm homicide rates in the US are 19 times greater than in France and 77 times greater than in Germany [[2]](https://www.healthdata.org/news-events/insights-blog/acting-data/gun-violence-united-states-outlier). It is a controversial debate however, as the question of gun ownership is a matter of constitutional right. In this project, we take an analytical approach to investigating the shooting data in the largest city in the US - New York City.

The dataset on which this analysis is built is the historic NYPD Shooting Incident Dataset which is available on the NYC OpenData portal. The dataset can be found [here](https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8/about_data). It contains details of every shooting incident in NYC in the time period 2006-2023. It has approximately 29000 observations each containing interesting features such as date, time and location of the shooting as well as age group, race and sex of both the perpetrator and the victim. 

* * *

## An overview of shooting incident data in NYC
To get a general overview of the number of shooting incidents in NYC, let us visualize how the number of shootings has changed with the years. In figure 1 we see the yearly number of shootings in all of NYC throughout the whole time period. The number of occurences appears relatively stable in the late 2010s followed by a period of significant drop in occurences until the large spike in 2020/2021. In 2022 and 2023 the number of occurences start dropping rapidly again. It is difficult to qualify what caused the prolonged drop in shooting incidents up until 2020, but it is not a phenomenon isolated to NYC. According to a report [[3]](https://bjs.ojp.gov/library/publications/trends-and-patterns-firearm-violence-1993-2018) by BJS, the rate of firearm violence declined significantly in the time period 1993-2018.

The surge of gun violence in 2020 can likely be attributed to a few factors. Firstly, the New York police department (NYPD) saw its resources stretched thin in 2020 due to the outbreak of the Covid-19 pandemic. Additionally, massive protests following the murder of George Floyd further weakened ability of the NYPD to be present in and around the city [[4]](https://www.nyc.gov/site/nypd/news/p0106a/overall-crime-new-york-city-reaches-record-low-2020).

![Fig1](assets/images/shootings_by_year.png)
> Figure 1: bla bla.........
