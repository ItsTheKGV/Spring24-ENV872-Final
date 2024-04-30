# <Spring24 ENV872 FINAL>

## Summary

This repository is Keanu Valibia's Github repository for his ENV872 Final. This repository contains the R Markdown file, and knitted PDF file for this World Bank data analysis project.

The goal of the project is to analyze basic energy consumption and development data for countries across the years 1990 - 2020 and understand any correlations with mortality rates for children under the age of five.  


## Investigators

Keanu Valibia, Duke University MPP/MEM student, keanu.valibia@duke.edu

## Keywords

WorldBank, API, EnergyUse, Oil, Renewable, RenewableEnergy, Mortality, MortalityRates

## Database Information

The data used in the project is sourced from the World Bank using the World Bank API via the "wb_data" RStudio function. The dataset was originally accessed on 4/30.

## Folder structure, file formats, and naming conventions 

###Folders

Final Project Code: Contains the actual code created to analyze the World Bank data as an R Markdown file.

Final Project Output: Contains the final knitted PDF file.

File naming convention: ENV872_FINAL_<File Purpose>

## Metadata

Source: World Bank API

EG.USE.PCAP.KG.OE: This data set describes the energy use per country in terms of kg of oil equivalent per capita. Original data is sourced from the IEA. This field is a"num" field, measured in terms of kg per capita.

HTML Source Link: https://data.worldbank.org/indicator/EG.USE.PCAP.KG.OE?view=chart

SH.DYN.MORT: This data set is an estimation of child mortality rates under the age of 5 per 1,000 live births. These estimates are developed by the UN Inter-agency Group for Child Mortality Estimation (UNICEF, World Health Organization, World Bank, United Nations Department of Economic and Social Affairs Population Division). This field is a "num" field, measured by number of deaths of children under the age of 5 for every 1,000 live births.

HTML Source Link: https://data.worldbank.org/indicator/SH.DYN.MORT?view=chart

EN.ATM.GHGT.KT.CE: This data set describes total greenhouse gas emissions as kilotons of CO2 equivalent. These estimates are developed by Climate Watch. This field is a "num" field, measured as total kilotons.

HTML Source Link: https://data.worldbank.org/indicator/EN.ATM.GHGT.KT.CE?view=chart

EG.FEC.RNEW.ZS: This data set tracks the estimated usage of renewable energies as a percentage of total final energy consumption. These estimates are developed by the IEA, IRENA, UNSD, World Bank, and World Health Organization. This field is a "num" field, measured as a percentage of total energy consumption of  a particular country.

HTML Source Link: https://data.worldbank.org/indicator/EG.FEC.RNEW.ZS?view=chart

<For each data file in the repository, describe the data contained in each column. Include the column name, a description of the information, the class of data, and any units associated with the data. Create a list or table for each data file.> 

## Scripts and code

This project uses R / RStudio for analysis of World Bank data.