# Avocado_Price

This dataset is taken from kaggle (https://www.kaggle.com/neuromusic/avocado-prices ) which sourced by website Hass Avocaco Board (https://hassavocadoboard.com).

This is how the data is described:

> The table below represents weekly 2018 retail scan data for National retail volume (units) and price. Retail scan data comes directly from retailers’ cash registers based on actual retail sales of Hass avocados. Starting in 2013, the table below reflects an expanded, multi-outlet retail data set. Multi-outlet reporting includes an aggregation of the following channels: grocery, mass, club, drug, dollar and military. The Average Price (of avocados) in the table reflects a per unit (per avocado) cost, even when multiple units (avocados) are sold in bags. The Product Lookup codes (PLU’s) in the table are only for Hass avocados. Other varieties of avocados (e.g. greenskins) are not included in this table.

Some relevant columns in the dataset:

`Date` - The date of the observation

`AveragePrice` - the average price of a single avocado

`type` - conventional or organic 

`year` - the year

`Region` - the city or region of the observation

`Total Volume` - Total number of avocados sold

`4046` - Total number of avocados with PLU 4046 sold (Small Hass)

`4225` - Total number of avocados with PLU 4225 sold (Large Hass)

`4770` - Total number of avocados with PLU 4770 sold (Extra Large Hass)

There are two files listed in this folder:

1. ipynb file describing all the details of the analysis : loading, cleaning, exploring and finally analysing
2. html file is the Summary report for the Avocado Price data.
