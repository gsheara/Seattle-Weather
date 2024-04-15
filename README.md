# Seattle-Weather
This repository is for the Seattle weather project. It will compare percipitation data collected from both Seattle and New York weather stations to determine which city experiences the most rainfall.
# Data 
The data used for this project contains two dataframes, one from New York weather stations and one from Seattle weather stations. This includes information about percipitation, date, location, among others, collected over the course of 2020 to 2023.

New York Data Set Link: https://github.com/gsheara/Seattle-Weather/blob/e34949f8fe3c82e2c1858e380be5d2c517d67f9f/ny_rain.csv

Seattle Data Set Link: https://github.com/gsheara/Seattle-Weather/blob/dbc8bb88f07899c70ba996b695aee64fb078f9e0/seattle_rain.csv

# Data preperation
From the raw data in the initial CSV files, Python libraries were used to clean the data by correcting data types, dropping unnecessary columns, removing duplicate rows, interpolating missing data, and making both values and metadata more legible. After that the two data frames were combined into one long format and exported as a CSV.

Data preparation notebook: https://github.com/gsheara/Seattle-Weather/blob/e8a19fdb589991b2aa4c2fddcaba302296a4b04e/GS_Data_Prep.ipynb 
