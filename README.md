# Seattle-Weather
This repository is for the Seattle weather project. It will compare percipitation data collected from both Seattle and New York weather stations to determine which city experiences the most rainfall.

# Description
The cleaned data set was analyzed to compare which city sees the highest quantity of rainfall and which sees the highest number of rainy days. The Altair-vega library for Python was used to build a number of visualizations, and accompanied by empirical statistics as well. Ultimately, NYC sees a higher quantity of rainfall and more days with heavy rain, while Seattle sees more days with any rain at all, and tends to have more months with rainy days across the year than NYC. NYC's distribution of rainy days across the year is more consistent, while Seattle has a spike in rainy days in the winter and dip in the summer months.

# Requirements
This project utilizes the CSV files included in this GitHub repository, Google Colab as a Python IDE, and a few common Python libraries for math and data visualization (pandas, numpy, matplotlib, and Altair-vega). 

# Data 
The data used for this project contains two dataframes, one from New York weather stations and one from Seattle weather stations. This includes information about percipitation, date, location, among others, collected over the course of 2020 to 2023.

New York Data Set Link: https://github.com/gsheara/Seattle-Weather/blob/e34949f8fe3c82e2c1858e380be5d2c517d67f9f/ny_rain.csv

Seattle Data Set Link: https://github.com/gsheara/Seattle-Weather/blob/dbc8bb88f07899c70ba996b695aee64fb078f9e0/seattle_rain.csv

# Data processing
From the raw data in the initial CSV files, Python libraries were used to clean the data by correcting data types, dropping unnecessary columns, removing duplicate rows, interpolating missing data, and making both values and metadata more legible. After that the two data frames were combined into one long format and exported as a CSV.

Data preparation notebook: https://github.com/gsheara/Seattle-Weather/blob/e8a19fdb589991b2aa4c2fddcaba302296a4b04e/GS_Data_Prep.ipynb 

Data analysis notebook: https://github.com/gsheara/Seattle-Weather/blob/15f7a31fff22f8ba2d6f9217d3bc157155f6a50c/GS_Analysis_Notebook.ipynb

# Authors
This project and corresponding repository was created by Genny Sheara for an assignment in DATA 3320: Data Methodologies at Seattle University.
LinkedIn: https://www.linkedin.com/in/genny-sheara/ 


# License
All data and tools utilized for this project are open source and reproducible by anyone.
