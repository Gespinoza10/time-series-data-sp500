# S&P 500 Stocks | Time Series Prophet Forecast Model

This program reads downloaded S&P 500 Stocks Data that you can find in the `archive` folder as `sp500_index.csv`. 
The dataset includes the stocks daily closing price for the last 10 years(`2013-2023`).

## Time Series Data Exploration 
Data is explored and analyzed per year `2022` and `2023`, it is also grouped by the last 5 years from `2018` to `2023`.

Data is also used to create a new feature in our dataframe `Return` that represents the stocks daily return. The program used `pandas` library `.diff()` function to calculate the daily retruns. 

## Creating a Time Series Model with Prophet
