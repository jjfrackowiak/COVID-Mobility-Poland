## COVID-Mobility-Poland

Project prepared in the summer semester 2022 for Digital Economy Education path co-organised by Warsaw Faculty of Economics and Google.<br />
Subject: Visualisation &amp; analysis of both global and region-specific trends in mobility during COVID 19 in Poland

Repository contains 3 elements: utilised Python code, .pdf report with visualisations and dynamic cartogram marking changes in mobility in retail sector on regional level.

## Mobility-related data sources
1) Global_mobility_report containing mobility data (source: https://www.google.com/covid19/mobility/?fbclid=IwAR0RXwUdoPpdzvM82VA6PaxgDZnuuxOskpJm9vEbKtvytsPirt7jutToflE), report with global data
4) Stay-at-home_covid (source: https://ourworldindata.org/covid-stay-home-restrictions)
5) WHO-COVID showing statistics on the course of the pandemic (number of new cases, number of deaths)

Google lists mobility statistics in 6 areas: trade and recreation, grocery stores and pharmacies, parks, stations and stops, workplaces and places of residence. We assumed that the analysis of the first area will be the most interesting: trade and recreation

There are two parts to the project:
1) Analysis of the mutual relations of statistics at the Polish level, extended by an analysis of the relationship between data on infections and the severity of restrictions applied and mobility in shopping and entertainment facilities.
2) Analysis of data on mobility in retail and entertainment facilities at the voivodeship level: Dynamic cartogram built using geojson library.

## Frames from dynamic cartogram

#### Percentage point change from the baselevel in mobility in retail sector (peak of infections in 2020):
![newplot (4)](https://github.com/jjfrackowiak/COVID-Mobility-Poland/assets/84077365/5890eea0-9e81-4c64-a515-33699da9e901)


#### Percentage point change from the baselevel in mobility in retail sector (holidays in 2020):
![newplot (3)](https://github.com/jjfrackowiak/COVID-Mobility-Poland/assets/84077365/2f11d933-9f14-4120-ace3-3e976e1e3cc3)
