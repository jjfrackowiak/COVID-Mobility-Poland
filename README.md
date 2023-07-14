## COVID-Mobility-Poland

Project prepared in the summer semester 2022 as a part of Digital Economy Education path co-organised by Warsaw Faculty of Economics and Google.<br />
Subject: Visualisation &amp; analysis of global and region-specific trends in mobility during COVID 19 in Poland

Repository contains following elements: 
- notebook with analysis and visualisations
- notebook creating dynamic cartogram marking changes in mobility in retail sector on regional level
- PDF report with visualisations and analysis (in Polish)
- data folder storing all data files except for sizeable 'Google_all.csv'
    - 'Google_all.csv' file can be downloaded from https://www.google.com/covid19/mobility/ and is unneccesary to create dynamic cartogram
      
Google lists mobility statistics in 6 areas: trade and recreation, grocery stores and pharmacies, parks, stations and stops, workplaces and places of residence. We assumed that the analysis of the first area will be the most interesting: trade and recreation

There are two parts to the project:
1) Analysis of the mutual relations of statistics at the Polish level, extended by an analysis of the relationship between data on infections and the severity of restrictions applied and mobility in shopping and entertainment facilities
2) Analysis of data on mobility in retail and entertainment facilities at the voivodeship level: Dynamic cartogram built using geojson library (defined in separate file: "Dynamic_cartogram.ipynb")

## Contents of 'data' folder
1) Files of structure '*PL_Mobility.csv' containing obility statistics for three years of pandemics reported by Polish regulators
2) 'Stay-at-home_covid.csv' containing information about imposed restrictions rigidity (source: https://ourworldindata.org/covid-stay-home-restrictions)
3) 'WHO-COVID.csv file' containing statistics on the course of the pandemic (number of new cases, number of deaths)
4) 'woj.geojson' file with coodinates of Poland administrative divisions (source: https://github.com/ppatrzyk/polska-geojson)


## Exemplary frames from dynamic cartogram

#### Percentage point change from the baselevel in mobility in retail sector (peak of infections in 2020):
![newplot (4)](https://github.com/jjfrackowiak/COVID-Mobility-Poland/assets/84077365/5890eea0-9e81-4c64-a515-33699da9e901)


#### Percentage point change from the baselevel in mobility in retail sector (holidays in 2020):
![newplot (3)](https://github.com/jjfrackowiak/COVID-Mobility-Poland/assets/84077365/2f11d933-9f14-4120-ace3-3e976e1e3cc3)
