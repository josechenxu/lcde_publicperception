# lcde_publicperception

This folder includes all the information about the cleaning and analysis of the Publi perception indicator for the Lancet Countdown in Europe 2026 Report.
Data were retrieved from GESIS - Leibniz-Institut für Sozialwissenschaften (https://search.gesis.org/) as they present individual level data with information about gender and urban-rural divide. 
Individual responses also allowed to understand which people selected climate and health simultaneously as top priorities for the country.

The main focus of this indicator is the question: "What do you think are the two most important issues facing <country> at the
moment?" 

Steps:
1) Download data and questionnaires for each round that includes the needed question
2) Understand differences in variables: different codes for each round from 2005-2012, different orders for the same questions from them on
3) Recoding variables manually to match the names of the variables and align other variables (i.e. gender and country)
4) Drop countries without complete data across the period.
5) Create variable "climate and health" as top priorities for the country.
6) Create year variable for each database
7) Combine datasets in common one.
8) Calculate rankings and percentages for 29 EEA countries for health, climate change, and climate+health
9) Conduct subregional analysis
10) Conduct analysis per gender and rural-urban divide
